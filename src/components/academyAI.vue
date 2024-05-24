<template>
    <div class="academy">
      <header class="header">
        <nav class="nav">
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Academy</a></li>
            <li><a href="#">Wake Up</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </nav>
      </header>
      
      <section class="intro">
        <h1>Passing our Knowledge and Expertise</h1>
        <p>To The Next Generation</p>
        <button class="pre-inscription-btn">Pre Inscription</button>
      </section>
      
      <section class="details">
        <p>From 1 June TO 30 June</p>
        <p>120h 550DT</p>
        <p>Limited Places 1 Month</p>
      </section>
      
      <section class="contact">
        <h2>Contact Us</h2>
      </section>
      
      <section class="about">
        <p>Herodot Studio is a gaming studio born from a passionate dream—to expand the cultural legacy of our ancestors to the world. Our team consists of 15 chaotic dreamers, united by a shared vision of a world where peace, creativity, and freedom flourish.</p>
      </section>
      
      <section class="course">
        <h2>Game Creation Lab</h2>
        <p>Number Of Hours</p>
        <p>Price</p>
        <p>Number</p>
        <p>Content Of The Course</p>
        <ul>
          <li>Game Dev + Drachnowa + Drachnowa</li>
          <li>Game Creation Process</li>
          <li>Coding</li>
          <li>Unity</li>
          <li>Game Design</li>
          <li>Personal Project</li>
        </ul>
      </section>
      
      <section class="experts">
        <h2>Our Experts</h2>
      </section>
      
      <section class="footer">
        <h2>Contact Us</h2>
      </section>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Academy'
  }
  </script>
  
  <style scoped>
  .academy {
    font-family: Arial, sans-serif;
  }
  
  .header {
    background: #333;
    padding: 10px 0;
  }
  
  .nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: space-around;
  }
  
  .nav li {
    margin: 0 10px;
  }
  
  .nav a {
    color: #fff;
    text-decoration: none;
  }
  
  .intro {
    text-align: center;
    background: url('@/assets/bolbol.jpg') no-repeat center center;
    background-size: cover;
    color: #fff;
    padding: 100px 20px;
  }
  
  .pre-inscription-btn {
    background-color: #ff9900;
    border: none;
    padding: 10px 20px;
    color: #fff;
    cursor: pointer;
  }
  
  .details, .about, .course, .experts, .footer {
    padding: 20px;
  }
  
  .details p, .about p, .course p, .experts p, .footer p {
    margin: 10px 0;
  }
  </style>
  