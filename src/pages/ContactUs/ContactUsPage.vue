<template>
  <div>
    <NavBar />
    <div class="container">
      <div class="flex">
        <div class="box-1">
          <h4>Reach Us</h4>
          <h3>Contact Buddies</h3>
          <p class="para-1">We are happy to help you, let us know your concern. </p>
          <p class="para-2">Pedals Up Buddy will not keep your personal or official user details. All information is about to security concern.</p>
          <div class="flex-2">
             <div>
              <img class="icon" src="../../assets/icons/phone.svg" alt="phone" />
              <p class="icon-text">+1234567 8910</p>
             </div>
             <div class="email-box">
              <img class="icon" src="../../assets/icons/email.svg" alt="email" />
              <p class="icon-text">help@buddy.com</p>
             </div>
          </div>
        </div>
        <div class="box-2">
          <img class="union" src="../../assets/icons/Union.svg" alt="union" />
          <!-- <img src="../../assets/icons/ellipse.jpg" alt="ellipse" /> -->
        </div>
      </div>
      <div class="card-container">
        <div class="card">
          <h4>Send your queries to us</h4>
          <h3>Contact Us</h3>
          <div class="input-holder">
            <input type="text" class="input-box" placeholder="Your Name" />
            <input type="text" class="input-box left" placeholder="Email Address" />
          </div>
          <div class="input-holder">
            <input type="text" class="input-box" placeholder="Phone Number" />
            <input type="text" class="input-box left" placeholder="Subject" />
          </div>
          <input type="text" class="message" placeholder="Type Your Message"/>
          <div class="try-now-btn">
            <h3>Submit</h3>
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
  name: "ContactUsPage",
  components: {
    NavBar
  }

}
</script>

<style scoped>
 .container {
  /* height: 90vh; */
  background-color: #011b0c;;
 }
 .flex {
  display: flex;
  padding: 0 250px;
  justify-content: space-between;
 }
 .box-1, .box-2 {
  width: 500px;
  height: 450px;
  /* background-color: red; */
 }
 .box-2 {
  /* background-color: yellow; */
  /* display: flex;
  justify-content: center; */
 }
  .box-1 h4, .card h4 {
  margin-top: 100px;
   font-size: 20px;
   color: #FFC700;
 }
 .box-1 h3, .card h3 {
   font-size: 48px;
   color: white;
   margin-top: 5px;
 }
 .para-1, .para-2{
  font-size: 14px;
  color: #798880;
  width: 500px;
  margin-top: 22px;
 }
 .para-2 {
  margin-top: 30px;
  width: 450px;
 }
 .icon {
  width: 18px;
 }
 .icon-text {
  color: white;
 }
 .flex-2 {
  display: flex;
  margin-top: 70px;
 }
 .email-box {
  margin-left: 130px;
 }
 .union {
  width: 150px;
  margin-top:80px;
  margin-left: 100px;
 }
 .card-container {
  height: 800px;
  /* background-color: red; */
  display: flex;
  justify-content: center;
 }
 .card {
  margin-top: 20px;
  width: 68%;
  height: 600px;
  background: linear-gradient(78.82deg, #002D13 0%, rgba(0, 45, 19, 0.2) 34.39%, rgba(0, 45, 19, 0.2) 72.93%, #002D13 99.78%);
  border-radius: 20px;
  box-shadow: 0 3px 10px rgb(0 0 0 / 0.2);
  padding: 10px 140px;
 }
 .input-holder {
   margin-top: 20px;
 }
 .input-box, .message {
  width: 350px;
  padding: 12px 0;
  border-radius: 30px;
  outline: none;
  border: none;
  padding-left: 15px;
  background: rgba(52, 168, 83, 0.2);
 }
 .left {
  margin-left: 30px;
 }
 .message {
  margin-top: 20px;
  width: 730px;
  height: 120px;
  padding: 0 auto;
 }
 .try-now-btn {
    margin-top: 30px;
    width: 150px;
    padding: 5px 7px;
    border-radius: 40px;
    background-color: #013f1b;
    display: flex;
    border: 1px solid #FFC700;
    align-items: center;
    color: black;
    cursor: pointer;
    justify-content: space-between;
  }
   .green-2 {
    width: 32px;
    height: 32px;
    background: #002D13;
    border-radius: 50%;
    border: 1px solid #FFC700;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .try-now-btn h3 {
    color: #FFC700;
    margin-bottom: 2px;
    font-weight: 600;
    font-size: 16px;
    margin-left: 10px;
  }
</style>