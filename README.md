# hello-world
Beginner
<!DOCTYPE html>
<html>
<head>
<meta charset = "UTF-8">
<link rel="stylesheet" type="text/css" href="1.css"/>
</style>
</head>
<body>
<h2>All About Cricket</h2>
<p>Bringing you news, stats, schedules and more from the world of cricket</p>
<hr>
<header>
<nav id="topnav">
  <ul>
    <li> <a href="News.html" title="News"> News </a> </li>
    <li> <a href="Fan Zone.html" title="Fan Zone"> Fan Zone </a> </li>
    <li> <a href="#" title="Polls"> Polls </a> </li>
    <li> <a href="Live Score.html" title="Live score"> Live Score </a> </li>
  </ul>
</nav>
</header>
<script type="text/javascript" style="align:right">
app=www.cricwaves.com"; mo="f1_zd"; nt="ban"; mats =""; tor =""; Width='302px'; Height='252px'; wi ="w";
co ="ban"; ad="1";
</script>
<script type="text/javascript" src="http://www.cricwaves.com/cricket/widgets/script/scoreWidgets.js"></script>
<br>
<br>
<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="ball.jpg" style="width:75%">
  <div class="text" text-align="Left">Image 1</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="cricket.jpg" style="width:75%">
  <div class="text" text-align="Left">Image 2</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="helmet.jpg" style="width:75%">
  <div class="text" text-align="Left">Image 3</div>
</div>

</div>
<br>

<div style="text-align:Left">
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
       slides[i].style.display = "none";
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>
<br>
<hr>
<footer>
CrickerIn &copy; </footer>
</body>
</html>
