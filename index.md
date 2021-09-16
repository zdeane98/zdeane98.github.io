<!DOCTYPE html>
<title>Zachary Deane</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Set the width of the sidebar to 120px */
.w3-sidebar {width: 120px;background: #222;}
/* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
#main {margin-left: 120px}
/* Remove margins from "page content" on small screens */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/ZachGray.jpg" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>PHOTOS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center" id="home">
    <h1 style="font-size:4vw;"><span class="w3-hide-small"></span> Zachary Deane</h1>
    <p>Quick Picture of Me (More to follow)</p>
    <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/PictureOfMe.PNG" alt="Zach" class="w3-image" width="364" height="419">
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">A Little About Me</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>Hi! My name is Zachary Deane. I am studying Cybersecurity at Saint Leo University. In my free time
      I enjoy playing video games, watching anime, and watching sports. I am usually pretty dominant in fantasy sports
      as I have many league championships under my belt. This year isn't looking great for me though! My favorite sports team
      is any team from Boston as I was born and raised in Massachussetts. My family likes to say that Tom Brady followed us to Tampa.
      My favorite anime is One Piece, if you also like One Piece please talk to me about it (I have some interesting theories). My favorite
      game changes with the wind. If you can find my steam profile in the large pool of "Zach" searches then please check out what I play.
      Below there should be some pictures, if you are curious the glorious cat is named Papillon and the gorgeous German Shepherd is named Suki.
    </p>


    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <a href="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/ZacharyDeaneResume.pdf" download="ZacharyDeaneResume" class="fa fa-download"></a> Download Resume
    </button>
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">My Photos</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/MonkeyDeaneLuffy.jpg" style="width:100%">
        <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/MeAndPapi.jpg" style="width:100%">
        <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/Suki.jpg" style="width:100%">
      </div>

      <div class="w3-half">
        <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/Group.jpg" style="width:100%">
        <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/Volleyball.jpg" style="width:100%">
        <img src="/Users/zdean/OneDrive/Documents/GitHub/zdeane98.github.io/SukiPuppy.jpg" style="width:100%">
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Tampa, FL</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: 339-832-8746</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: zachdeane98@gmail.com</p>
    </div><br>

  <!-- End Contact Section -->
  </div>

<!-- END PAGE CONTENT -->
</div>
