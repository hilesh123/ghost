<!-- <template>
  <div v-if="!isLoggedIn">
  
    <div class="container_main">
      <div>
        <h1>Sign-in</h1>
      </div>
      <h1 class="Sign-in-text"></h1>
      <input placeholder="Enter username...." v-model="a" />
      <input placeholder="Enter password...." v-model="b" />
      <div>
        <button @click="signin">Sign-in</button>
      </div>
      <h1 class="pop" v-if="boolean">{{ arr }}</h1>
    </div>
  </div>

  <div v-if='isLoggedIn'>
   
    <h1>Welcome to Home!</h1>
  
  </div>
</template>

<script setup>
import { ref } from "vue";

let a = ref("");
let b = ref("");
let boolean = ref(false);
let arr = ref("");
let isLoggedIn = ref(false);

function signin() {
  if (a.value === "hilesh" && b.value === "hilesh123") {
    isLoggedIn.value = true;
  } else {
    boolean.value = true;
    arr.value = "Invalid username or Password";
  }
}
</script>
<style>
body{
    color: rgb(235, 235, 235);
}
.container_main{
color: black;
border: 0.2rem solid white;
width: 20rem;
height: 14rem;
border-radius: 0.5rem;

}

button{
    width: 80px;
    height: 40px;
    font-size: 12.5px;
    margin-left: 0.7rem;
    margin-top: 1rem;
    border: 2px solid grey;
}
input{
    margin-top: 1rem;
border: 2px solid grey;
    border-radius: 0.5rem;
    text-align: center;
font: 0.8em sans-serif;
}
h1{
    font-size: 29px;
    color: rgb(255, 255, 255);
    background-color: orangered;

}
.pop{

   margin-bottom: 70px; 
   border-radius: 0.5rem;
   font-size: 10px;
}
</style> -->

<!-- <template>
    <input v-model='input' type='text'/>
    <button @click="entered">add</button>
    <h1 v-if="entered">{{b}}</h1>
</template>
<script setup>
import {ref} from "vue"
let input=ref("");
let b=ref()
function entered(){
    b.value=input.value;
}

</script>
<style>
input{
width: 12rem;
height: 2rem;
margin-bottom: 1rem;
border: 1px solid red;
background-color: black;
border-radius: 0.5rem;
text-align: center;


}
button{
    width: 5rem;
    height: 2.5rem;
    margin-left: 1rem;
    color: rgb(192, 0, 0);
    border: 1px solid red;
    background-color: black;
    border-radius: 0.5rem;
  
}
</style> -->
<!-- <template>

  <div class="login_1">
  <img src="C:\Users\HP\Desktop\vue project\vite-project\photo_2024-09-08_15-53-19.jpg"/>
  <h1>Log-in</h1>
  <div class="login_2">
  <h3>username</h3>
  <input type="password"/>
  <h3>enter password</h3>
   <input/>
  
  </div>
  <div>
    <button class="buttons">login</button></div>
 
  </div>
</template>
<style>
.login_1{
  width: 280px;
  height: 475px;
  border:2px solid goldenrod;
  border-radius: 0.5rem;

  

}
.login_2{




}
.buttons{
  color:goldenrod;
  border: 2px solid goldenrod;
  border-radius: 0.5rem;
  height: 5px;
  width: 85px;

padding-bottom: 2rem;
margin-top: 0.5rem;



}
input{
  border: 2px solid goldenrod;
  border-radius: 0.5rem;
  margin-bottom: 1rem;
}
h1{
  font-size: 2rem;
}
h3{
  font-size: 0.9rem;
}
img{
  width: 17.5rem;
  height: 9rem;
}
</style> -->



<!-- 
Here's your updated code with proper alignment and corrections:

<template>
  <div class="container_main">
    <div class="container_1">
      <div class="logo">
      <h1>Aether Cure</h1>
      </div>
      <div class="title">
        <h1>Where AI Meets Healthy Living.</h1>
      </div>
      <div class="title_1">
        <h4>Spend less time registering, more time on your health.
</h4>
      </div>
      <div class="description"></div>
    </div>
    <div class="container_2">
      <div class="top_2">
        <h1>Get Started</h1>
        <h3 class="create">Sign-in</h3>
        
      </div>
          
      <div class="details">
  
<button class="google-btn">Continue with Google</button>
     
        <h2>Email</h2>
        <input type="email"  placeholder="John@123..."/>
        <h2>Password</h2>
        <input type="password" placeholder="Password"/>
        <button>Signin</button>
        <div class="signin-container">
          <span class="signin">New user?</span>
          <a>Register</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .container_main {
    width: 45rem;
    height: 30rem;
    background-color: white;
    border-radius: 0.5rem;
    margin-left: 20rem;
    margin-top: 5rem;
    display: flex;
  }

  body {
    background-color: grey;
    background: url('photo_2024-09-08_15-53-19.jpg');
  }

  .container_1 {
    width: 23rem;
    height: 28.6rem;
    background-color: rgb(179, 170, 170);
    margin-top: 10px;
    margin-left: 10px;
    margin-bottom: 10px;
    border-radius: 0.5rem;
    display: flex;
    flex-direction: column;
  }

  .logo {
font-size: 20px;
height: 3rem;
margin-left: 23px;
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  
  }

  .title {
    margin-top: 45px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 11px;
    margin-left: 25px;
    width: 20rem;
    height: 5rem;
    max-width: 35em;
    line-height: 40px;
  }

  .description {
    background-color: rgb(52, 56, 56);
    width: 20rem;
    height: 10rem;
    margin-left: 12px;
    border-radius: 0.5rem;
    margin-top: 30px;
  }

  .title_1 {
    margin-left: 25px;
    color: rgb(122, 112, 112);
    width: 19.5rem;
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
font-size: 15px;
  }

  .container_2 {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }

  .details {
    font-size: 8px;
    color: grey;
    margin-left: 50px;
  margin-bottom: 100rem;
  }

  input {
    height: 1.5rem;
    width: 15rem;
  }

  button {
 
    height: 2.2rem;
    width: 15rem;
    border-radius: 1rem;
    color: rgb(224, 224, 224);
    font-size: 15px;
    margin-top: 1.5rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: #fc1d1d;

  }

  .top_2 {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin-right: 85px;
    height: 7.5rem;
  
  }

  .create {
    color: grey;
    font-size: 25px;
    
  }

  a {
    color: rgb(0, 0, 255);
    font-size: 12px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-decoration: underline;
  }

  .signin-container {
    display: flex;
    align-items: center;
    margin-left: 50px;
  }

  .signin {
    color: rgb(15, 13, 13);
    font-size: 12px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin-right: 10px;
  }
  .google-btn {
    width: 15.4rem;
    height: 2rem;
    background-color: #fff;
    border: 1px solid #000000;
    border-radius: 0.5rem;
    font-size: 15px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
   

  
    color: #000;
  }
  </style>-->
<template>
  <div class="weird-loader-container">
    <h2 v-if="showHeading" class="weird-heading"> What if they’re watching....?</h2> <!-- Conditional heading -->
    <div class="weird-loading-bar">
      <div class="bar" :style="{ width: loadingWidth + '%' }"></div>
      <div class="eyes">
        <div class="eye" v-for="n in 2" :key="n">
          <div class="pupil"></div>
        </div>
      </div>
      <div class="dino" :style="{ left: `${loadingWidth}%` }">
        <p>🦖</p>
      </div>
    </div>
    <p class="loading-text">{{ loadingMessage }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      loadingWidth: 0,
      loadingMessage: "Why are you waiting? This is getting weird...",
      showHeading: false, // Controls the visibility of the heading
    };
  },
  mounted() {
    this.startLoading();
    setTimeout(() => {
      this.showHeading = true; // Show heading after 5 seconds
    }, 5000);
  },
  methods: {
    startLoading() {
      const interval = setInterval(() => {
        if (this.loadingWidth >= 100) {
          clearInterval(interval);
          this.loadingMessage = "Done... Or are we?";
        } else {
          this.loadingWidth += Math.random() * 10; // Randomize loading increments
        }
      }, 300); // Speed of loading
    },
  },
};
</script>

<style scoped>
.weird-loader-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: black; /* Black background for ghost effect */
}

.weird-heading {
  font-size: 24px;
  color: #ffffff; /* White color for visibility */
  font-family: 'Comic Sans MS', cursive, sans-serif; /* Consistent font */
  margin-bottom: 20px; /* Spacing below the heading */
  text-align: center; /* Center the heading */
  animation: fadeIn 1s; /* Optional fade-in animation */
}

.weird-loading-bar {
  position: relative;
  width: 80%;
  height: 30px;
  border: 5px solid #ffffff; /* White border for contrast */
  background-color: rgba(255, 255, 255, 0.2); /* Translucent background */
  overflow: hidden;
  border-radius: 15px;
  box-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
}

.bar {
  height: 100%;
  background-color: rgba(117, 255, 3, 0.8); /* Light green for ghostly effect */
  transition: width 0.3s ease;
}

.eyes {
  position: absolute;
  top: -30px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  justify-content: space-between;
  width: 40px;
}

.eye {
  width: 15px;
  height: 15px;
  background-color: #fff; /* White for eyes */
  border-radius: 50%;
  position: relative;
}

.pupil {
  width: 5px;
  height: 5px;
  background-color: black; /* Black pupils for contrast */
  border-radius: 50%;
  position: absolute;
  top: 5px;
  left: 5px;
  transition: all 0.1s ease;
}

.dino {
  position: absolute;
  top: -40px; /* Adjust the height as needed */
  font-size: 30px; /* Size of the dinosaur */
  animation: moveDino 3s infinite;
}

.loading-text {
  margin-top: 20px;
  font-size: 18px;
  color: #d32f2f;
  font-family: 'Comic Sans MS', cursive, sans-serif;
  text-align: center;
  animation: shake 0.5s infinite alternate;
}

@keyframes shake {
  0% { transform: translateX(0); }
  100% { transform: translateX(-5px); }
}

@keyframes moveDino {
  0% { transform: translateX(0); }
  100% { transform: translateX(-20px); }
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
</style>
