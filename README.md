<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Alexa Baker</title>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
		<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
		<style>
			body {
				font: 20px Montserrat, sans-serif;
				line-height: 1.8;
				color: #f5f6f7;
			}
			.bgimg-1 {
    			background-image: url('http://bsnscb.com/data/out/156/39249587-programmer-wallpapers.png');
    			min-height: 100%;
                background-attachment: fixed;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
                padding-top: 700px;
				padding-bottom: 700px;
			}
			.bg-2 { 
				background-color: #474e5d; /* Dark Blue */
				color: #ffffff;
			}
			.bg-3 { 
				background-color: #fff; /* White */
				color: #555555;
			}
			.bg-4 { 
				background-color: #000000; /* Black */
				color: #ffffff;
			}
			.bg-5 { 
				background-color: #456788; /* gray-blueish */
				color: #ffffff;
			}
			.container-fluid {
				padding-top: 70px;
				padding-bottom: 70px;
			}
			.navbar {
				padding-top: 15px;
				padding-bottom: 10px;
				border: 0;
				border-radius: 0;
				margin-bottom: 0;
				font-size: 12px;
				letter-spacing: 5px;
                position:fixed;
                top:0;
                width: 100%;
                z-index:99999;
			}
			.navbar-nav  li a:hover {
				color: #1abc9c !important;
			}
            /* Turn off parallax scrolling for tablets and phones */
            @media only screen and (max-device-width: 1024px) {
                .bgimg-1{
              		background-attachment: scroll;
                }
		  </style>
	</head>
<body>
      
      <nav class="navbar navbar-default">
		<div class="container">
			<div class="navbar-header">
				<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>  
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
				</button>
				<a class="navbar-brand" href="#">ALEXA BAKER</a>
			</div>
			<div class="collapse navbar-collapse" id="myNavbar">
				<ul class="nav navbar-nav navbar-right">
					<li><a href="#">HOME</a></li>
					<li><a href="#">ABOUT</a></li>
					<li><a href="#">RESUME</a></li>
					<li><a href="#">WORK</a></li>
					<li><a href="#">CONTACT</a></li>
				</ul>
			</div>
		</div>
	</nav>

	<div class="bgimg-1 w3-display-container container-fluid text-center w3-opacity-min" id="home">
      <div class="w3-display-middle" style="white-space:nowrap;">
        <br><br><br><h1> Hello World!</h1><br><br><br><br>
      </div>
    </div>
	
	<div class="container-fluid bg-2 text-center">
		<h3>About Me Page</h3>
		<p>:)</p>
	</div>

	<div class="container-fluid bg-3 text-center">
		<h3>Resume and qualifications</h3>
		<p>:)</p>
	</div>
	
	<div class="container-fluid bg-4 text-center">
		<h3>Work Experience, Projects, and Portfolio Stuff</h3><br>
		<div class="row">
			<div class="col-sm-4">
			<p>Work Projs.</p>
			<img src="http://www.printawallpaper.com/upload/designs/coffee_at_work_detail.jpg" 
			class="img-responsive" style="width:100%" alt="Image">
			</div>
			<div class="col-sm-4"> 
				<p>School Projs</p>
				<img src="http://wallpapercave.com/wp/1KcNGtr.jpg" 
				class="img-responsive" style="width:100%" alt="Image">
			</div>
			<div class="col-sm-4"> 
				<p>Fun Projs</p>
				<img src="http://hdqwalls.com/wallpapers/programming-world-map-on.jpg" 
				class="img-responsive" style="width:100%" alt="Image">
			</div>
		</div>
	</div>
	
	<footer class="container-fluid bg-5 text-center">
		<h3>Contact</h3>
		<p>:)</p>
	</footer>
    
</body>
</html>
