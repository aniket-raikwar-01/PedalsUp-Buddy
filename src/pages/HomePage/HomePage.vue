<template>
  <div>
    <NavBar />
    <div class="container">
      <div class="box">
        <h4>Chat, write, and get work done</h4>
        <h3>Come for Secure chat.</h3>
        <h3>Stay for our Encryption Model.</h3>
        <p class="para-1">We make customer messaging apps for sales, marketing, and support, </p>
        <p class="para-2">connected on one platform with hi-tech encryption model.</p>
        <div class="yellow-btn">
          <div class="green">
            <img src="../../assets/icons/metamask.svg" alt="metamask" />
          </div>
          <h3>Connect Metamask</h3>
        </div>
      </div>
      <div>
        <div class="card-container">
          <div class="card1"></div>
          <div class="card2"></div>
          <div class="card3"></div>
          <div class="card4"></div>
          <div class="card5"></div>
        </div>
        <div>
          <div class="tag-line-container">
            <div class="tag-line">
              <div class="line"></div>
              <p>A channel for every conversation</p>
            </div>
            <div class="tag-line">
              <div class="line"></div>
              <p>Conversation with high level encryption security.</p>
            </div>
            <div class="tag-line">
              <div class="line"></div>
              <p>No Fake Promises</p>
            </div>
          </div>
        </div>
      </div>
      <div class="role-module">
        <div class="box-1">
          <div class="card-box">
            <div class="card-one"></div>
            <div class="card-two"></div>
          </div>
          <div class="card-three"></div>
        </div>
        <div class="box-2">
          <h3>Role Module</h3>
          <h1>Targeted</h1>
          <h1>engagement at</h1>
          <h1>scale</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean dui sem, consequat vel scelerisque sit amet, imperdiet a neque. Vestibulum fermentum, ipsum eget rutrum varius, nisl lorem fringilla nulla, sed blandit neque libero id quam.</p>
          <div class="try-now-btn">
            <h3>Try Now</h3>
            <div class="green-2">
              <img src="../../assets/icons/right-arrow.svg" alt="arrow" />
            </div>
        </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "../../components/Navbar/NavBar.vue";

export default {
  name: "HomePage",
  components: {
    NavBar,
  }

}
</script>

<style scoped>
 .container {
  height: 90vh;
  background-color: #002D13;
  /* display: flex;
  justify-content: center; */
  /* align-items: center; */
 }
 .box {
  /* margin-top: 100px; */
  /* background-color:red; */
  display: flex;
  flex-direction: column;
  height: 300px;
  align-items: center;
 }
 .box h4 {
  margin-top: 100px;
   font-size: 20px;
   color: #FFC700;
 }
 .box h3 {
   font-size: 48px;
   color: white;
   margin-top: 5px;
 }
 .para-1, .para-2{
  font-size: 14px;
  color: #798880;
  width: 500px;
  margin-top: 10px;
  text-align: center;
 }
 .para-1 {
  margin-top: 25px;
 }

 .yellow-btn, .try-now-btn {
    margin-top: 30px;
    padding: 5px 7px;
    border-radius: 40px;
    background-color: #013f1b;
    display: flex;
    border: 1px solid #FFC700;
    align-items: center;
    color: black;
    cursor: pointer;
  }
  .yellow-btn h3{
    margin-left: 5px;
    color: #FFC700;
    margin-right: 8px;
    letter-spacing: -0.2px;
    font-size: 14px;
    margin-bottom: 5px;
  }
  .green, .green-2 {
    width: 32px;
    height: 32px;
    background: #002D13;
    border-radius: 50%;
    border: 1px solid #FFC700;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .green img {
    width: 18px;
  }
  .green-2 img {
    width: 12px;
  }
  .card-container {
    display: flex;
    height: 350px;
    justify-content: center;
    margin-top: 160px;
    /* background: red; */
     background: linear-gradient(0deg, #001508, #002D13 60%) ;
  }
  .card1, .card2, .card3, .card4, .card5 {
    width: 160px;
    height: 200px;
    margin-left: 50px;
    background: #005739;
    border-radius: 20px;
    transform: rotate(-20deg);
  }
  .card1{
    margin-top: 80px;
    margin-right: -50px;
  }
  .card2 {
    width: 200px;
    height: 260px;
    margin-top: -50px;
  }
  .card3 {
    width: 240px;
    height: 310px;
    margin-left: 80px;
    background: linear-gradient(0deg, #001509, #005739 80%) ;
  }
  .card4 {
    width: 180px;
    height: 230px;
  }
  .card5 {
    width: 200px;
    height: 240px;
    margin-top: 50px;
  }
  .tag-line-container {
    height: 200px;
    /* background-color: red; */
    background: linear-gradient(0deg, #002D13, #001508 80%) ;
    display: flex;
    padding: 0px 250px;
    justify-content: space-between;
  }
  
  .line {
    width: 100px;
    margin-top: 30px;
    height: 4px;
    border-radius: 20px;
    background-color: #FFC700;
  }
  .tag-line p{
    color: white;
    font-size: 18px;
    margin-top: 15px;
    width: 230px;
  }
  .role-module {
    height: 600px;
    display: flex;
    padding: 0 210px;
    justify-content: space-between;
    background-color: #002D13;
  }
  .box-1 {
     margin-top: 100px;
     width: 500px;
  }
  .box-2 {
     margin-top: 100px;
     width: 500px;
  }
  .box-2 h3 {
    color: #FFC700;
    font-weight: 400;
    font-size: 18px;
    margin-bottom: 10px;
  }
  .box-2 h1{
    font-size: 40px;
    color: white;
  }
  .box-2 p {
    color: #798880;
    margin-top: 20px;
    line-height: 23px;
    font-size: 16px;
  }
  .try-now-btn {
    width: 140px;
    justify-content: space-between;
    background: #FFC700;
  }
  .try-now-btn h3 {
    color: #002D13;
    margin-bottom: 2px;
    font-weight: 600;
    font-size: 16px;
    margin-left: 10px;
  }
  .arrow {
    width: 5px;
  }
  .card-box {
    display: flex;
    justify-content: right;
    align-items: center;
  }
  .card-one, .card-two, .card-three {
    width: 220px;
    height: 300px;
    background-color: #005739;
    border-radius: 15px;

  }
  .card-one {
    margin-right: 30px;
  }

  .card-two {
    width: 150px;
    height: 150px;
  }
  .card-three {
    width: 310px;
    height: 180px;
    float: right;
    margin-top: -40px;
    z-index: 9;
    box-shadow: rgba(146, 145, 145, 0.05) 0px 6px 24px 0px, rgba(162, 161, 161, 0.08) 0px 0px 0px 1px;
  }

</style>