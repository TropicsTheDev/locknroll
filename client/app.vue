<template>
  <body class="background-clr">

    <nav class="nav-bar">
      <h1>LOCK N' ROLL PROMOTIONS</h1>

      <ul class="main-menu">
        <li><a href="">Home</a></li>
        <li><a href="">Buy Tickets</a></li>
        <li><a href="">Upcoming Seminars</a></li>
        <li><a href="">Contact</a></li>

        <!-- <li><button id="tickets-button" class="nav-btn" >Buy Tickets</button></li> -->
      </ul>
    </nav>

    <div class="seminar-img">
      a
    </div>

    <footer class="footer">
      <div class="footer-container">
        footer n shieeeeet
      </div>
    </footer>

  </body>
</template>

<style>
  .seminar-img {
    background-color: white;
    height: 50vh;
    width: 50vh;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .footer-container {
    background-color: white;
    width: 100%;
    height: 10%;
    position: absolute;
    bottom: 0;
  }
  .background-clr {
    background-color: #191923
  }
  .nav-bar {
    background-color: white;
  }
  .main-menu {
    list-style-type: none;
    padding: 0px;
    margin: 0px;
    overflow: hidden;
  }
  .main-menu a{
    text-decoration: none;
    color: black;
    display: block;
    text-align: center;
    padding: 15px;
  }
  .main-menu a:hover{
    background-color: #E1DFF6
  }
  .main-menu li{
    float: left;
  }
</style>

