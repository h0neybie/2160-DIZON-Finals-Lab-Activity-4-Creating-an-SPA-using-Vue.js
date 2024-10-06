<template>
   <div id="profile" >
  <header class=" text-black py-5 col-12" style="background-color: 	#a27eab; color: #ffff !important; ">
  <div class="container">
    <div class="row">
      <div class="col-md-3 text-left text-md-center mb-3 ">
        <img  src="../assets/profile.jpg" alt="Profile Photo" />
      </div>
      <div class="border-top pt-3 col-md-9 mt-3" style="color: #ffff !important;"> <br>
        <h1 style="color: #ffff !important;">Abby Cruz Dizon</h1>
        <h5 style="color: #ffff !important;">Freelance Web Developer</h5><br>
        <p>
            San Nicolas 1st Lubao, Pampanga <br>   
            abbydizon1023@gmail.com  <br>
            09669407251  <br></p><br> <hr >
      </div>       
    </div>        
  </div>
</header>
                               
    </div>
  </template>
  
  <script>
  export default {
    name: 'Profile',
    data () {
      return {
        msg6: 'This is the Profile page.'
      }
    }
  }
  </script>
  
  <style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  
  h1, h2 {
    font-weight: normal;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  li {
    display: inline-block;
    margin: 0 10px;
  }
  
  a {
    color: #d199ca;
  }
  
  img{
    border-radius: 10% 10% 10% 10%;
    height: 310px;
    width: auto;
  }
.profile-img{box-shadow: 0 5px 15px rgba(0,0,0,.5)}


  
  </style>
  