# portfolio_task1

<!DOCTYPE html>
<html>
<title>PortFolio Website</title>
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
  <img src="C:\Users\Admin\Downloads\ishu1.png" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
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
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">I'm</span> Ishwari Nalawade</h1>
    <p>Computer Engineer</p>
   <img src="c:\Users\Admin\Downloads\ishu.png.jpg" width="600" height="500">
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">I'm Ishwari Nalawade</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>
	Thanks for your interest, here
								is a quick story of me and this
								website.
								
								I Ishwari Nalawade So Currently I am pursuing My Btech Degree In Computer science & engineering in SKN Sinhgad college of Engineering 
								Korti Pandharpur
								Now About My Technical Knowledge I have interest in web development Angular etc.
								

								I do my work mainly in HTML CSS & java& also DSA using java
								Besides this i known about the c,mysql database ass well.
							

								This website is basically one of my
								Web Development project which is
								built using HTML only.
								

								Thanks again for reading this
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
    <p class="w3-wide">HTML</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">CSS</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">JAVA programming</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
    
    

    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download"></i> Download Resume
    </button>
    
    <!-- Grid for pricing tables -->
    <h3 class="w3-padding-16 w3-text-light-grey">My Projects</h3>
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half w3-margin-bottom">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Basic</li>
          <li class="w3-padding-16">Simple Calculater</li>
          <li class="w3-padding-16">To Do List</li>
          <li class="w3-padding-16">Charity Webpage</li>
		  <li class="w3-padding-16">Biography page</li>
         
            
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">take Look</button>
          </li>
        </ul>
      </div>

      <div class="w3-half">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Pro</li>
          <li class="w3-padding-16">Landing Pages</li>
          <li class="w3-padding-16">Charity responsible website</li>
          <li class="w3-padding-16">Tourism website</li>
          <li class="w3-padding-16">Coaching classes website</li>
         
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Take Look</button>
          </li>
        </ul>
      </div>
    <!-- End Grid/Pricing tables -->
    </div>
    
  </div>
    <!-- Testimonials -->
    <h3 class="w3-padding-24 w3-text-light-grey">My Qualification</h3>  
    
    <p><span class="w3-large w3-margin-right">SSC</span>92%</p>
    
    
    
    <p><span class="w3-large w3-margin-right">HSC</span> 91.60%</p>
	
	 <p><span class="w3-large w3-margin-right">Pursuing BTECH</span></p>
    
	
  <!-- End About Section -->
  </div>
  
 

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Sangola</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: +8767671524</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: ishwarinalawade15@gmail.com</p>
    </div><br>
    <p>Let's get in touch. Send me a message:</p>

    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
  
    <!-- Footer -->
  <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    <p class="w3-medium">Created By Ishwari<a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green"></a></p>
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>
