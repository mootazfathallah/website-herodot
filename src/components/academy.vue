<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-center-item">
        <div class="menu-item">
          <div class="menu-text">
            About Us
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-text">
            Portfolio
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-text" style="color:rgb(255, 206, 32, 100%)">
            Academy
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-text">
            Wake Up
          </div>
        </div>
      </div>
      <div class="menu-right-item">
        <div class="menu-text">
          Contact Us
        </div>
      </div>
    </div>
    <div class="intro">
      <div class="title">
        Passing Our Knowledge and Expertise
      </div>
      <div class="title" style="padding-left: 180px;">
        To The Next Generation
      </div>
      <div class="content">
        Herodot Studio is a gaming studio born from a passionate dream—to expand the cultural legacy of our ancestors to the world. Our team consists of 15 chaotic dreamers, united by a shared vision of a world where peace, creativity, and freedom flourish.
      </div>
      <div class="introButtons">
        <div class="button">
          Pre Inscription
        </div>
        <div class="button">
          Contact Us
        </div>
      </div>
    </div>
    <div style="padding-top: 20px;">
      <div class="hr-wrapper">
        <div class="hr-part"></div>
        <div class="hr-gap"></div>
        <div class="hr-part"></div>
      </div>
    </div>
    <div class="course-info">
      <div style="margin-left: 8%; margin-bottom: 60px;">
        <div style="font-size: 60px;text-align: left;">
          GAME <br>CREATION LAB 
        </div>
        <div style="color: rgba(82, 5, 208, 1);text-align: right; padding-top: 20px; font-size: 18px;">
          From 1st of June To 30th of June
        </div>
      </div>
      <div style="margin-right: 3%;">
        <div style="display: flex;border:#ffffff 1px solid; border-radius: 5px; justify-content: center; padding-top: 20px; padding-bottom: 20px; padding-left: 10px; padding-right: 10px; margin-top:40px ;">
          <div class="displayNumber">
            Number Of Hours <br>
            <span style="color: rgb(255, 206, 32, 100%);">120h</span><br>
            <span style="color: rgb(255, 206, 32, 100%); font-size: 10px;">1 Month</span>
          </div>
          <div class="displayNumber" style="margin-right: 80px; margin-left: 20px;">
            Price<br>
            <span style="color: rgb(255, 206, 32, 100%);">550DT</span>
          </div>
          <div class="displayNumber">
            Number <br>
            <span style="color: rgb(255, 206, 32, 100%);">15</span><br>
            <span style="color: rgb(255, 206, 32, 100%); font-size: 10px;">Limited Places</span>
          </div>
        </div>
        <div style="padding-top: 20px; text-align: center; width: 650px;">
          Herodot Studio is a gaming studio born from a passionate dream—to expand the cultural legacy of our ancestors to the world. Our team consists of 15 chaotic dreamers, united by a shared vision of a world where peace, creativity, and freedom flourish.
        </div>
        <div class="button" style="margin-top: 20px; margin-left: 28%;">
          Pre Inscription
        </div>
      </div>
    </div>
    <div style="margin-top: 120px;">
      <div class="Course" style="margin-left: 8%;">
        <div class="courseTitle">
          Content Of The Course
        </div>
        <div style="font-size: 20px;">
          hay khoukha katlek drachnouwa drachnouwa
        </div>
      </div>
      <div style="margin-top: 60px;">
        <div class="courseProcess" style="margin-left: 0%;">
          <img src="../assets/Group 418.png" height="300px" width="1300px">
        </div>
      </div>
    </div>
    <div style="display: flex; justify-content:space-evenly; margin-top: 60px; margin-bottom: 40px;">
        <div class="ImageUnity">
          <img src="../assets/image 54.png" height="70px" width="150px">
        </div>
        <div class="ImageUnity">
          <img src="../assets/image 54.png" height="70px" width="150px">
        </div>
        <div class="ImageUnity">
          <img src="../assets/image 54.png" height="70px" width="150px">
        </div>
        <div class="ImageUnity">
          <img src="../assets/image 54.png" height="70px" width="150px">
        </div>        
    </div>
    <div style="padding-top: 20px;">
      <div class="hr-wrapper">
        <div class="hr-part"></div>
        <div class="hr-gap"></div>
        <div class="hr-part"></div>
      </div>
    </div>
    <div style="margin-bottom: 80px;">
      <div style="font-size: 40px; text-align: center; margin-top: 20px; margin-bottom: 30px;">
          Our Experts
      </div>
      <div style="display: flex;justify-content: space-evenly;">
        <div>
          <img src="../assets/bolbol.jpg" height="300px" width="550px">
        </div>  
        <div>
          <img src="../assets/bolbol.jpg" height="300px" width="550px">
        </div>        
      </div>      
    </div>
    <hr style="margin: 20px auto; height:1px; background-color:rgb(159, 189, 255); border: none;">  
    <div class="contactUs" style="text-align: center; padding-top: 60px; font-size: 40px; padding-bottom: 80px;">
      <div class="contactUsText" style="transition: 0.5s; cursor: pointer;">Contact Us</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'academy',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .menu {
  display: flex;
  justify-content: space-around;
  height: 40px;
  border-bottom: 2px solid;
}

.menu-center-item {
  margin-left: 300px;
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu-item {
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu-right-item {
  flex: 1;
  text-align: center;
  display: flex;
  height: 20px;
  justify-content: right;
  align-items: right;
}

.menu-text{
  font-size: 20px;
  color: #ffffff;
  cursor: pointer;
  padding: 10px;
  width: fit-content;
  transition: 0.5s;
}

.menu-text:hover {
  color: rgb(255, 206, 32, 100%);
}

.intro{
  text-align: center;
  margin-top: 50px;
}
.intro::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url('@/assets/Ellipse 1.png') no-repeat center right;
  background-size: 800px;
  z-index: -1;
}

.title{
  margin-top: 50px;
  font-size: 40px;
}

.content{
  margin: 50px auto 30px auto;
  width: 750px;
}

.introButtons{
  display: flex;
  margin-top: 30px;
  margin-bottom: 30px;
  justify-content: center;
  flex: 1;
  text-align: center;
}

.button{
  border: #ffffff 1px solid;
  border-radius: 5px;
  width: 250px;
  padding-top: 7px;
  padding-bottom: 7px;
  margin: 15px;
  color: rgb(255, 206, 32, 100%);
  font-size: 25px;
  font-weight:bold;
  transition: all 0.5s;
  cursor: pointer;
}

.button:hover{
  background-color:rgba(82, 5, 208, 1);
}
.hr-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}

.hr-part {
  width: 35%; 
  height: 2px; 
  background-color: #FFCE20; 
}

.hr-gap {
  width: 30%; 
  height: 2px; 
}

.displayNumber{
  font-size: 20px;
  padding-left: 20px;
  padding-right: 20px;
  padding-top: 10px;
  padding-bottom: 10px;
}

.Course{
  border-left: 5px solid rgba(82, 5, 208, 1);
  margin-left: 2%;
  padding-left: 10px;
  text-align: left;
}

.course-info {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  color: #fff;
  height: 400px;
  overflow: hidden;
}

.course-info::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url('@/assets/bolbol.jpg') no-repeat center center fixed;
  background-size: cover;
  opacity: 0.2; /* 10% visibility */
  filter: blur(2px); /* Apply blur effect */
  z-index: -1; /* Place it behind the content */
}

.course-info::content{
  background: url('@/assets/Ellipse 1.png') no-repeat center left;
  background-size: 600px;
}
.courseTitle{
  font-size: 40px;
  padding-bottom: 10px;
}

.contactUs{
  background: url('@/assets/Ellipse 7.png') no-repeat center bottom;
  background-size: 600px;
}

.contactUsText:hover{
  color: rgb(255, 206, 32, 100%);
}
</style>
