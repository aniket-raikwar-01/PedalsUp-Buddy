<template>
  <nav class="navbar">
    <div class="nav-container">
       <img class="logo" src="../../assets/icons/logo.svg" alt="logo" />
       <div class="nav-items">
        <h3>Home</h3>
        <h3>About Us</h3>
        <h3>Team</h3>
        <h3>Contact Us</h3>
        <div class="yellow-btn">
          <div class="green">
            <img src="../../assets/icons/metamask.svg" alt="metamask" />
          </div>
          <h3>Connect</h3>
        </div>
       </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',

}
</script>

<style scoped>
  .navbar {
    height: 80px;
    background: #002D13;
    padding: 0 40px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo {
   width: 9%;
  }
  .nav-container {
    display: flex;
    width: 80%;
    justify-content: space-between;
    align-items: center;
    /* background-color: red; */
  }

  .nav-items {
    width: 40%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: white;
    font-size: 12px;
    letter-spacing:0.3px;
    font-weight: 300;
  }

  .yellow-btn {
    padding: 5px 7px;
    border-radius: 40px;
    background-color:#FFC700;
    display: flex;
    align-items: center;
    color: black;
    cursor: pointer;
  }

  .yellow-btn h3{
    margin-left: 5px;
    color: black;
    margin-right: 8px;
    letter-spacing: -0.2px;
  }



  .green {
    width: 32px;
    height: 32px;
    background: #002D13;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .green img {
    width: 18px;
  }
</style>