 i am kinsman 
 
<!DOCTYPE html>
<html>
<head>
    <title>KINSMAN@RESUME</title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Kinsman is free PSD &amp; HTML template by @Kinsman">
    <meta name="author" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="css/kube.min.css" />
    <link rel="stylesheet" href="css/font-awesome.min.css" />
    <link rel="stylesheet" href="css/custom.min.css" />
    <link rel="shortcut icon" href="img/favicon.png" />
	<link href='https://fonts.googleapis.com/css?family=Playfair+Display+SC:700' rel='stylesheet' type='text/css'>
	<link href='https://fonts.googleapis.com/css?family=Lato:400,700' rel='stylesheet' type='text/css'>
	<style>
		.intro h1:before {
			
			content: 'KINSMAN U';
		}
	</style>
</head>
<body>
	<!-- Navigation -->
	<div class="main-nav">
		<div class="container">
			<header class="group top-nav">
				<div class="navigation-toggle" data-tools="navigation-toggle" data-target="#navbar-1">
				    <span class="logo">KINSMAN U</span>
				</div>
			    <nav id="navbar-1" class="navbar item-nav">
				    <ul>
				        <li class="active"><a href="#about">About</a></li>
				        <li><a href="#Projects">Projects</a></li>
				        <li><a href="#achievements">Achievements</a></li>
				        <li><a href="#skills">Skills</a></li>
				    </ul>
				</nav>
			</header>
		</div>
	</div>

	<!-- Introduction -->
	<div class="intro section" id="about">
		<div class="container">
			<p>Hi, I'm Kinsman</p>
			<div class="units-row units-split wrap">
				<div class="unit-20">
					<img src="img/ava.jpg" alt="Avatar">
				</div>
				<div class="unit-80">
					<h1>I AM <br><span id="typed"></span></h1>
				</div>
				<p>
					As a driven and motivated young professional, I bring a combination of passion, adaptability, and a strong work ethic to every task. With a background in [Designing the web page], I have honed my skills in [Html,css,js], allowing me to As a employee.
				</p>
			</div>
		</div>
	</div>

	
	<div class="Project section second" id="Projects">
		<div class="container">
			<h1>PERSONAL<br>PROJECT</h1>
			<ul class="Projects-list">
				<li>Open Weaver - Periyorudan </li>
				<li> Done a Web development project on open waver a no coding platform</li>
                <li>Made for the aged people to work with the ai tools to teach their grandchildren </li>
			</ul>
		</div>
	</div>

	<!-- Award & Achievements -->
	<div class="Achievements section second" id="achievements">
		<div class="container">
			<h1>Achievements<br>In my life</h1>
			<ol class="Short-list list-flat">
				<li>1. Shortlisted in companies after the completion of Diploma (Nokia,Forti) </li>

				<li>2. Participated in national level hackathon</li>

				<li>3. I was best defender ever in our local football team</li>
			</ol>
		</div>
	</div>


	<div class="skills section second" id="skills">
		<div class="container">
			<h1>Technical<br>Skills</h1>
			<ul class="skill-list list-flat">
				<li>Web Technology</li>
				<li>HTML / CSS / Javascript</li>
			</ul>
			<ul class="skill-list list-flat">
				<li>Database</li>
				<li>MySQL / MongoDB</li>
			</ul>
		</div> 
	</div>             



	<div class="quote">
		<div class="container text-centered">
			<h1>I LOVE DESIGNING.</h1>
		</div>
	</div>

	<footer>
		<div class="container">
			<div class="units-row">
			    <div class="unit-50">
			    	<p>Handcrafted by KINSMAN U</p>
			    </div>
			    <div class="unit-50">
					<ul class="social list-flat right">
						<li><a href="mailto:Kinsman.25cs@licet.ac.in"><i class="fa fa-send"></i></a></li>
						<li><a href="https://github.com/Kinsman2003 "><i class="fa fa-github"></i></a></li>
					</ul>
			    </div>
			</div>
		</div>
	</footer>

	<!-- Javascript -->
	<script src="js/jquery.min.js"></script>
	<script src="js/typed.min.js"></script>
    <script src="js/kube.min.js"></script>
    <script src="js/site.js"></script>
    <script>
		function newTyped(){}$(function(){$("#typed").typed({
			
		strings: ["KINSMAN", "FROM LOYOLA COLLEGE", "INTERESTED IN DESIGNING"],

		typeSpeed:90,backDelay:700,contentType:"html",loop:!0,resetCallback:function(){newTyped()}}),$(".reset").click(function(){$("#typed").typed("reset")})});
    </script>

<style>/* Global Styles */

	body {
		font-family: 'Lato', sans-serif;
		line-height: 1.6;
		background-color: #f5f5f5;
		color: #333;
		margin: 0;
		padding: 0;
	}
	
	.container {
		width: 90%;
		margin: 0 auto;
	}
	
	/* Navigation */
	
	.main-nav {
		background-color: #333;
		color: #fff;
		padding: 10px 0;
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		z-index: 1000;
	}
	
	.main-nav .logo {
		font-family: 'Playfair Display SC', serif;
		font-size: 1.5em;
		font-weight: bold;
		text-transform: uppercase;
	}
	
	.main-nav nav ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		text-align: center;
	}
	
	.main-nav nav ul li {
		display: inline-block;
		margin-right: 20px;
	}
	
	.main-nav nav ul li a {
		color: #fff;
		text-decoration: none;
		font-size: 1.2em;
		transition: all 0.3s ease;
	}
	
	.main-nav nav ul li a:hover {
		color: #ffc107; /* change to your preferred hover color */
	}
	
	/* Introduction Section */
	
	.intro {
		padding: 100px 0;
		text-align: center;
		background-color: #fff;
	}
	
	.intro p {
		font-size: 1.2em;
		margin-bottom: 20px;
		color: #726464;
	}
	
	.intro h1 {
		font-family: 'Playfair Display SC', serif;
		font-size: 3em;
		font-weight: 700;
		margin-bottom: 20px;
		position: relative;
	}
	
	.intro h1:before {
		content: '';
		position: absolute;
		bottom: -10px;
		left: 50%;
		transform: translateX(-50%);
		width: 50%;
		height: 2px;
		background-color: #333;
	}
	
	.intro .unit-20 {
		text-align: center;
	}
	
	.intro .unit-20 img {
		border-radius: 50%;
		width: 150px;
		height: 150px;
		border: 5px solid #333;
		transition: all 0.3s ease;
	}
	
	.intro .unit-20 img:hover {
		transform: scale(1.1);
	}
	
	.intro .unit-80 {
		text-align: left;
		padding-left: 20px;
	}
	
	.intro .unit-80 p {
		font-size: 1.1em;
		line-height: 1.8;
		color: #777;
	}
	
	/* Project Section */
	
	.Project {
		padding: 80px 0;
		text-align: center;
		background-color: #f9f9f9;
	}
	
	.Project h1 {
		font-family: 'Playfair Display SC', serif;
		font-size: 3em;
		font-weight: 700;
		margin-bottom: 40px;
	}
	
	.Project .Projects-list {
		list-style-type: none;
		padding: 0;
		text-align: left;
	}
	
	.Project .Projects-list li {
		font-size: 1.1em;
		margin-bottom: 20px;
	}
	
	/* Achievements Section */
	
	.Achievements {
		padding: 80px 0;
		text-align: center;
		background-color: #fff;
	}
	
	.Achievements h1 {
		font-family: 'Playfair Display SC', serif;
		font-size: 3em;
		font-weight: 700;
		margin-bottom: 40px;
	}
	
	.Achievements .Short-list {
		list-style-type: none;
		padding: 0;
		text-align: left;
	}
	
	.Achievements .Short-list li {
		font-size: 1.1em;
		margin-bottom: 20px;
	}
	
	/* Skills Section */
	
	.skills {
		padding: 80px 0;
		text-align: center;
		background-color: #f9f9f9;
	}
	
	.skills h1 {
		font-family: 'Playfair Display SC', serif;
		font-size: 3em;
		font-weight: 700;
		margin-bottom: 40px;
	}
	
	.skills .skill-list {
		list-style-type: none;
		padding: 0;
		text-align: left;
	}
	
	.skills .skill-list li {
		font-size: 1.1em;
		margin-bottom: 15px;
	}
	
	/* Quote Section */
	
	.quote {
		padding: 80px 0;
		text-align: center;
		background-color: #333;
		color: #fff;
	}
	
	.quote h1 {
		font-family: 'Playfair Display SC', serif;
		font-size: 3em;
		font-weight: 700;
		margin-bottom: 20px;
	}
	
	/* Footer */
	
	footer {
		background-color: #333;
		color: #fff;
		padding: 20px 0;
		text-align: center;
	}
	
	footer p {
		font-size: 1em;
		margin: 0;
	}
	
	footer .social {
		list-style-type: none;
		padding: 0;
		margin: 10px 0 0 0;
	}
	
	footer .social li {
		display: inline-block;
		margin-right: 10px;
	}
	
	footer .social li a {
		color: #fff;
		font-size: 1.5em;
		transition: all 0.3s ease;
	}
	
	footer .social li a:hover {
		color: #ffc107; /* change to your preferred hover color */
	}
	</style>

	
	
</body>
</html>
