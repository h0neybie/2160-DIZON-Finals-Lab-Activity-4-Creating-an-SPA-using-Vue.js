<template>
  <div id="app">
    <hr>
    <img src="./assets/1.png">
    <h1>{{ msg }}</h1>
    <about-us> </about-us> 
    <profile></profile>
    <education></education>
    <skills></skills>
  </div>
</template>

<script>

import AboutUs from './components/AboutUs.vue'
import Profile from './components/Profile.vue'
import Education from './components/Education.vue'
import Skills from './components/Skills.vue'


export default {
  name: 'app',
  components: { AboutUs, Profile, Education, Skills},
  data () {
    return {
      msg: 'Welcome to Your Vue.js App, Shinobu!'
    }
  }
}

</script>

<style>
#app {
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif !important;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #36243b;
  margin: 0px 0px;
 
}

h1, h2, h5 {
  font-weight: normal;
    color: #000 !important;
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
  border-radius: 15% 15% 15% 15%;
}

#profile{
display: flex !important; 
justify-content: center !important;
}

  body{margin-top:20px;}
.section {
    padding: 100px 0;
    position: relative;
}
.gray-bg {
    background-color: #f5f5f5;
}
.section-title h2 {
    font-weight: 700;
    color: #000;  
    font-size: 45px;
    margin: 0 0 15px;
    border-left: 5px solid #9b6f95 !important;
    padding-left: 15px;
}
.section-title {
    padding-bottom: 45px;
}
.section-title p {
    margin: 0;
    font-size: 18px;
}

/* Resume Box
---------------------*/
.resume-box {
  background: #ffffff;
  box-shadow: 0 0 1.25rem rgba(31, 45, 61, 0.08);
  border-radius: 10px;
}
.resume-box ul {
  margin: 0;
  padding: 30px 20px;
  list-style: none;
}
.resume-box li {
  position: relative;
  padding: 0 20px 0 60px;
  margin: 0 0 30px;
}
.resume-box li:last-child {
  margin-bottom: 0;
}
.resume-box li:after {
  content: "";
  position: absolute;
  top: 0px;
  left: 20px;
  border-left: 1px dashed #9b6f95 !important;
  bottom: 0;
}
.resume-box .icon {
  width: 40px;
  height: 40px;
  position: absolute;
  left: 0;
  right: 0;
  color: #c489bc !important;
  line-height: 40px;
  background: #ffffff;
  text-align: center;
  z-index: 1;
  border: 1px dashed;
  border-radius: 50%;
}
.resume-box .time {
  background: #c489bc  !important;
  color: #ffffff;
  font-size: 10px;
  padding: 2px 10px;
  display: inline-block;
  margin-bottom: 12px;
  border-radius: 20px;
  font-weight: 600;
}
.resume-box h5 {
  font-weight: 700;
  color: #000;
  font-size: 16px;
  margin-bottom: 10px;
}
.resume-box p {
  margin: 0;
}

.resume-box li:after {
    content: "";
    position: absolute;
    top: 0px;
    left: 20px;
    border-left: 1px dashed #d199ca  !important;
    bottom: 0;
}

</style>
