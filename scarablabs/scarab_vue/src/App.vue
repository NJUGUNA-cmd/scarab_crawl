<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
<div class="webname"><img src="./assets/bitmap1.png" alt=""></div>
    <div class="wrapper">
      
      <div class="mobile tod">
        <img src="./assets/combined 2.png">
      </div>
    </div>
  </header>
  <div class="about">
      <img src="./assets/GO180.png" class="3">
      <img src="./assets/pipes.jpg" class="4">
      <img src="./assets/gym.png" class="5">
      <img src="./assets/hardware.png" class="6">

  </div>
<div class="services">
  <!--solo prenuers planning section-->
  <div class="smallbiz">
    <div class="n-tb pcw">Personal custom website</div>
    <div class="price">Ksh.15,000</div>
    <div class="what-r-d">
      We offer designing and making custom websites for personal use at negotiable prices.<br/>
      Pricing differs according to the complexity of the web page while Scarab Crawl ensures you get QUALITY results
      <br/>
      <ul>
        <li>Hosting and domain name</li>
      </ul>
    </div>
    <button class="sus">CONTACT US</button>
  </div>
  <!--Sme's-->
  <div class="smallbiz">
    <div class="n-tb">SME'S</div>
    <div class="price">Ksh.55,000</div>
    <div class="what-r-d">
      Small scale but important,we value your commitment and it's why our key focus is on the growth of SME's by giving 
      affordable and reliable service to you.<br/>
      <ul>
        <li>Hosting and domain name</li>
        <li>SEO</li>
      </ul>
    </div>
    <button class="sus">CONTACT US</button>
  </div>
  <!--Ecommerce websites-->
  <div class="smallbiz">
    <div class="n-tb">E-commerce Website</div>
    <div class="price">Ksh.100,000</div>
    <div class="what-r-d">
      Get your e-commerce website with a proffessional design and custom functionality
      <br/>
      <ul>
        <li>Hosting and domain name</li>
        <li>SEO</li>
      </ul>
    </div>
    <button class="sus">CONTACT US</button>
  </div>
</div>
<footer>
  ABOUT | CONTACTS
  <BR/>
  Scarab-Crawl is a group of independent programmers and designers committed to provide 
  affordable and customizable<br/> web-applications and multi-platform an IOS, ANDROID, WINDOWS
  and MAC-OS for small bussinesses and personal blogs.<br/>
  <BR/>
  REACH OUT
  <BR/>
  You can contact our lead programmer through zosarian@gmail.com or 0785369962
  <BR/>
  <BR/>
  <BR/>
  <BR/>
  <BR/>

  <div class="copy">  copyright 2024</div>

</footer>
</template>
<style scoped>
*
{
  background-color: rgb(255, 255, 255);
}
ul
{
  background-color:rgba(97, 58, 7, 0);
}
ul li
{
  background-color:rgba(97, 58, 7, 0);
  text-align: left;
}
.webname
{
  border-style: solid;
  border-width: 1px;
  width: 100%;
  height: 60px;
  background-color: rgb(0, 0, 0);
}
.webname > img{
  height: 56px;
  margin-left: 20px;
}
header {
  background-color: rgb(255, 255, 255);
  min-height:300px;
}
.wrapper
{
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
  opacity: 1;
}
.tod
{
  border-style: solid;
  border-width: 0px;
  width: 95%;
  height: fit-content;
  border-color: green;
}
.tod > img
{
  width: 100%;
  height: 80%;
  object-fit: contain;
}
.about{
  width: 100%;
  height: 500px;
  background-color: rgba(255, 255, 255, 0);
  border-style: solid;
  border-width: 0ch;
  border-color: rgb(97, 58, 7);
  overflow: hidden;
  display: grid;
  overflow: hidden;
  --d: 20s;
  justify-content: center;
  align-items: center;
}
.about > img{
  grid-area: 1/1;
  aspect-ratio: 1.5;
  object-fit: cover;
  animation: r var(--d) linear infinite;
  width:300px;
  border-radius: 7px;
  width: 70%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0);
}
.about > img:nth-child(1) {animation-delay: calc(1*var(--d)/-4)}
.about > img:nth-child(2) {animation-delay: calc(2*var(--d)/-4)}
.about > img:nth-child(3) {animation-delay: calc(3*var(--d)/-4)}
.about > img:nth-child(4) {animation-delay: calc(4*var(--d)/-4)}
.about > img:nth-child(5) {animation-delay: calc(5*var(--d)/-4)}


@keyframes r {
  70%    {transform: translate(-300%)}
  70.01% {transform: translate( 100%)}
}

.services{
  width:100%;
  height: 480px;
  background-color: rgb(0, 0, 0);
  border-style: solid;
  border-width: 0px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.smallbiz
{
  border-style: solid;
  border-width: 0px;
  border-radius: 15px;
  width:335px;
  height: 400px;
  margin-left: 50px;
  margin-top: 10px;
  background-image: linear-gradient(to top, #b224ef 0%, #7579ff 100%);
}
.smallbiz:hover
{
  height: 420px;
  transition-duration: 0.5s;
}
.smallbiz >.n-tb
{
  border-style: solid;
  border-width: 0px;
  width: 100%;
  height:60px;
  position: relative;
  margin-top: 10px;
  background-color: #757aff00;
  text-align: center;
  justify-content: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: x-large;
  font-weight: bolder;
  color: rgb(255, 255, 255);
  padding: 10px;
  letter-spacing: 1px;
  
}
.smallbiz .pcw
{
  text-align: left;
  word-spacing: 0px;
}
.price
{
  border-style: solid;
  width: 100%;
  height: 70px;
  border-width: 0px;
  background-color: #00000000;
  justify-content: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: x-large;
  font-weight: 900;
  color: rgb(13, 180, 7);
  padding: 10px;
}
.what-r-d
{
  border-style: solid;
  border-width: 0px;
  width:100%;
  height: 170px;
  background-color: #757aff00;
  font-weight: bolder;
  font-size: medium;
  text-align: center;
}
.sus
{
  border-style: solid;
  border-width: 2px;
  border-color: white;
  width:70%;
  height: 50px;
  border-radius: 50px;
  margin: 20px 0px 0px 15%;
  background-color: #757aff00;
  justify-content: center;
  font-family:cursive;
  font-size: large;
  font-weight: bolder;
  color: rgb(73, 238, 8);
}
footer{
  width:100%;
  min-height: 300px;
  background-color: rgb(0, 0, 0);
  border-style: solid;
  border-width: 0px;
  color: white;
}
.copy
{
  width: 100px;
  height: 40px;
  background-color:#00000000;
  margin-left: 45%;
}
</style>
