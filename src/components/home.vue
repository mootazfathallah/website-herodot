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
          <div class="menu-text">
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
        WELCOME TO
        HERODOT STUDIO!
      </div>
      <div class="content">
        barcha ktiiba
      </div>
      <div class="tags">
         <div class="tag">
          <span style='color:rgb(255, 206, 32, 100%);'>100%</span> Tunisian
         </div>
         <div class="tag">
          Since <span style='color:rgb(255, 206, 32, 100%);'>2018</span>
        </div>
        <div class="tag">
          <span style='color:rgb(255, 206, 32, 100%);'>15</span> Members
        </div>
        <div class="tag">
          <span style='color:rgb(255, 206, 32, 100%);'>6</span> Finished Projects
        </div>
      </div>
    </div>
    <div Class="titleSmall" style="text-align: left;padding-left: 100px;">
        Check out our Projects
    </div>
    <div class="projects">
      <div class="project">
        <div class="projectImage">
          <img src="../assets/bolbol.jpg" height="150px" width="150px">
        </div>
        <div class="projectDescription"> 
          Project description
        </div>
      </div>
      <div class="project">
        <div class="projectImage">
          <img src="../assets/bolbol.jpg" height="150px" width="150px">
        </div>
        <div class="projectDescription"> 
          Project description
        </div>
      </div>
    </div>
    <hr style="width:75%;height: 2px;color: black;background-color:black">
    <div class="latestGame">
      <div class="gameIntro">
        <div class="gameTitle">
          Latest Game <span style='color:rgba(82, 5, 208, 1);'>Wake Up</span>
        </div>
        <div class="gameDesc">
          ktiiba
        </div>
      </div>
      <div class="gameDetails">
        <div class="gameTrailer">
          <img src="../assets/bolbol.jpg" height="250px" width="250px">
        </div>
        <div class="gameDescription">
          barcha ktiiba
        </div>
      </div>
    </div>
    <div class="partnersBloc">
        <div class="titleSmall" style="text-align: center; padding-bottom: 15px;">
          WHO TRUSTED US
        </div>
        <div class="partnersDesc">
          ktiiba
        </div>
        <div class="partners">
          <div class="partner">
            <div class="partnerImage">
              <img src="../assets/bolbol.jpg" height="100px" width="100px">
            </div>
            <div class="partnerDesc">
              ktiiba
            </div>
          </div>
          <div class="partner">
            <div class="partnerImage">
              <img src="../assets/bolbol.jpg" height="100px" width="100px">
            </div>
            <div class="partnerDesc">
              ktiiba
            </div>
          </div>
          <div class="partner">
            <div class="partnerImage">
              <img src="../assets/bolbol.jpg" height="100px" width="100px">
            </div>
            <div class="partnerDesc">
              ktiiba
            </div>
          </div>
          <div class="partner">
            <div class="partnerImage">
              <img src="../assets/bolbol.jpg" height="100px" width="100px">
            </div>
            <div class="partnerDesc">
              ktiiba
            </div>
          </div>
        </div>
    </div>
    <hr style="width:75%;height: 0.2px;color: black;background-color:black">
    <div class="carrers">
      <div class="carrersIntro">
        <div class="carrersTitle">
          HERODOT SHARING CARRER
        </div>
        <div>
          
        </div>
      </div>
    </div>    
  </div>
</template>

<script>
export default {
  name: 'home',
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
}

.menu-text:hover {
  color: rgb(255, 206, 32, 100%);
}

.intro{
  text-align: left;
  margin-top: 100px;
  margin-left: 100px;
}

.title{
  font-size: 40px;
  width: 400px;
}

.content{
  padding-top: 10px;
}
.tags{
  display: flex;
  justify-content: left;
  padding-top: 10px;
}

.tag{
  padding-left: 10px;
}

.titleSmall{
  font-size: 20px;
  padding-top: 100px;
}
.projects{
  display: flex;
  justify-content: left;
  padding-top: 10px;
  padding-left: 100px;
  padding-bottom: 40px;
}

.project{
  display: flex;
  justify-content: left;
  padding-top: 10px;
}

.latestGame{
  padding-top: 30px;
  padding-left: 100px;
  padding-bottom: 40px;
}

.gameIntro{
  border-left: 5px solid rgba(82, 5, 208, 1);
  padding-left: 10px;
  text-align: left;
}

.gameTitle{
  font-size: 20px;
}

.gameDetails{
  display: flex;
  justify-content: left;
  padding-top: 30px;
}

.partnersBloc{
  padding-bottom: 40px;
}
.partners{
  display: flex;
  justify-content: center;
  padding-top: 40px;
}
.partner{
  padding: 10px;
  margin-left: 10px;
  margin-right: 10px;
  border-style:groove ;
}
</style>
