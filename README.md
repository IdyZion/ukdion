<!DOCTYPE html>
<html lang="en-US">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
	<title>IdyZion</title>

	<!-- Latest compiled and minified CSS -->
	<link rel="stylesheet" href="css/bootstrap.min.css">
	<!-- Main Styles -->
	<link rel="stylesheet" href="assets/styles/style.min.css">
	   
	<!-- Themify Icon -->
	<link rel="stylesheet" href="assets/fonts/themify-icons/themify-icons.css">

	<!-- Button Icons-->
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

	<style>

		.container-fluid {
			  background-color: black;
			  padding: 10px;
			}

		.container-fluid a {
			  text-align: center;
			  padding: 14px 16px;
			  font-size: 14px;
			}

		.container-fluid .search-container {
		  float: left;
		  padding-top: 15px;
		  padding-left: 5px;
		  background-color: black;
		}


		max-width: 600px {
		  .container-fluid .search-container {
		    float: none;
		  }
		 
	</style>

	<style>

		.subnav {
		  overflow: hidden;
		  background-color: white;
		}

		.subnav a {
		  float: left;
		  text-align: center;
		  padding: 14px 16px;
		  font-size: 14px;
		  margin-top: 100px;
		}

		.subnav a:hover {
		  border-bottom: 2px solid grey;
		}

		.subnav a.active {
		  border-bottom: 2px solid red;
		}
	</style>
</head>

<body style="background-color: white;">
	<nav class="navbar navbar-inverse navbar-fixed-top">
	  	<div class="container-fluid">

	    	<div class="navbar-header">
	      		<button type="button" class="btn btn-default btn-sm">
	      			<img src="images/logo.jpg">
	      		</button>
	      	</div>

	      	<div class="search-container" id="idNavbar">
			    <form action="/action_page.php">
			      <input type="text" placeholder="Search or jump to..." name="search">
			      <button type="submit"><i>/</i></button>
			    </form>
			</div>
			<div class="collapse navbar-collapse" id="idNavbar">
	      		<ul class="nav navbar-nav">
	       			<li>
	        			<a href="#">
	          				<span><b style="color: white;">Pull requests</b></span>
	        			</a>
	        		</li>
	        		<li>
	        			<a href="#">
	          				<span><b style="color: white;">Issues</b></span>
	        			</a>
	        		</li>
	        		<li>
	        			<a href="#">
	          				<span><b style="color: white;">Marketplace</b></span>
	        			</a>
	        		</li>
			        <li>
			        	<a href="#">
			          		<span><b style="color: white;">Explore</b></span>
			        	</a>
			        </li>
	        		        
	      		</ul>
	      		<ul class="nav navbar-nav navbar-right">
			        <li>
			        	<a href="#">
			          		<span class="glyphicon glyphicon-bell" style="color: white;"></span>
			        	</a>
			        </li>
			        <li class="dropdown">
			          	<a class="dropdown-toggle" data-toggle="dropdown" href="#">
			          		<span class="glyphicon glyphicon-plus" style="color: white;"></span>
			          		<span class="caret" style="color: white;"></span>
			        	</a>
			          	<ul class="dropdown-menu">
				            <li><a href="#">New repository</a></li>
				            <li><a href="#">Import repository</a></li>
				            <li><a href="#">New gist</a></li>
				            <li><a href="#">New organization</a></li>
				            <li><a href="#">New project</a></li>
			          	</ul>
	        		</li>
	        		
	        		<li style="padding: 10px;">
	        			<img src="images/avatar.png" class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" width="28" height="28" style="border-radius: 13px;" >
	        			<span class="caret" style="color: white;"></span>
	        		</li>
			        
	      		</ul>
	     	</div>
	    </div>  
	</nav>

	<div class="subnav" >
	  <a>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</a>
	  <a class="active" href="#"> Overview</a>
	  <a href="#">Repositories</a>
	  <a href="#">Projects</a>
	  <a href="#">Packages</a>
	  <hr style="width:100%;text-align:left;margin-left:0">
	</div>

		<div class="col-md-3">
			<div class="card" style= "border: 3px; padding: 30px; align-content: center;">
				    <p>
				    	<img class="img-circle card-img-top" src="images/avatar.png" alt="Card image" style= "align-content: center;">
				    </p>
				    <div class="card-body">
					    <p class="card-title" style="font-size: 20px;">IdyZion</p>
					    <a href="#" class="btn btn-default stretched-link"><b style="color: black;">&nbsp &nbsp &nbsp &nbsp &nbsp&nbsp &nbsp Edit Profile &nbsp&nbsp&nbsp &nbsp &nbsp &nbsp &nbsp</b></a>
					</div>
			</div>
		</div>

		<div class="col-md-9">
			<div class="alert alert-info alert-dismissible" style="margin-right: 50px; padding-left: 40px;">
			    <button type="button" style="color: blue;" class="close" data-dismiss="alert">&times;</button>
			    <strong>ProTip!</strong> Updating your profile with your name, location, and a profile picture helps other GitHub users get to &nbsp &nbsp &nbsp &nbsp &nbsp&nbsp &nbsp <button class="btn btn-success btn-sm"><i class="fa fa-edit"></i> Edit Profile</button> <br>  know you.
			    
			</div>

			<div>
				<p style="border-top: 200px; font-size: 14px;">Popular repositories</p>
				<p style="border-top: 400px; text-align: center; font-size: 20px;"><b>You don’t have any public repositories yet.</b></p>
				<p style="border-top: 600px; font-size: 14px;">1 contribution in the last year 
					<a href="#" style="color: black; text-align: right;">Contribution settings</a>
					<span class="caret" style="color: black;"></span>
				</p>
			</div>

			<div>
				<p style="font-size: 20px; text-align: center;">Choose an ecosystem</p>
			</div>
			<div class="row">
				<div class="col-md-4 col-xs-12">
					<div class="box-content card" style="padding: 10px; padding-left: 30px; padding-right: 40px; border-radius: 5px;">
						<h5><i class="fa ico"><img src="images/docker.png"></i> <b style="font-size: 20px;">Docker</b></h5>
						<p style="font-size: 12px;">A software platform used for building applications based on containers — small and lightweight execution environments.</p>
						<button type="button" class="btn btn-default btn-sm" style="border-radius: 4px;">Learn More</button><br><br>
					</div>					
				</div>
				<div class="col-md-4 col-xs-12">
					<div class="box-content card" style="padding: 10px; padding-left: 30px; padding-right: 40px; border-radius: 5px;">
						<h5><i class="fa ico"><img src="images/apache.png"></i> <b style="font-size: 20px;">Apache Maven</b></h5>
						<p style="font-size: 12px;">A default package manager used for the Java programming language and the Java runtime environment.</p>
						<button type="button" class="btn btn-default btn-sm" style="border-radius: 4px;">Learn More</button><br><br>
					</div>
				</div>
				<div class="col-md-4 col-xs-12">
					<div class="box-content card" style="padding: 10px; padding-left: 30px; padding-right: 40px; border-radius: 5px;">
						<h5><i class="fa ico"><img src="images/nuget.jpg"></i> <b style="font-size: 20px;">NuGet</b></h5>
						<p style="font-size: 12px;">A free and open source package manager used for the Microsoft development platforms including .NET.</p>
						<button type="button" class="btn btn-default btn-sm" style="border-radius: 4px;">Learn More</button><br><br>
					</div>
				</div>
			</div>
			<div class="row" style="background-color: white;">
				<div class="col-md-4 col-xs-12">
					<div class="box-content card" style="padding: 10px; padding-left: 30px; padding-right: 40px; border-radius: 5px;">
						<h5><i class="fa ico"><img src="images/rubygems.png"></i> <b style="font-size: 20px;">RubyGem</b></h5>
						<p style="font-size: 12px;">A standard format for distributing Ruby programs and libraries used for the Ruby programming language.</p>
						<button type="button" class="btn btn-default btn-sm" style="border-radius: 4px;">Learn More</button><br><br>
					</div>
				</div>
				<div class="col-md-4 col-xs-12">
					<div class="box-content card" style="padding: 10px; padding-left: 30px; padding-right: 40px; border-radius: 5px;">
						<h5><i class="fa ico"><img src="images/npm.jpg"></i> <b style="font-size: 20px;">npm</b></h5>
						<p style="font-size: 12px;">A package manager for JavaScript, included with Node.js. npm makes it easy for developers to share and reuse code.</p>
						<button type="button" class="btn btn-default btn-sm" style="border-radius: 4px;">Learn More</button><br><br>
					</div>
				</div>
				<div class="col-md-4 col-xs-12">
					<div class="box-content card" style="padding: 10px; padding-left: 30px; padding-right: 40px; border-radius: 5px;">
						<h5><i class="fa ico"><img src="images/docker.png"></i> <b style="font-size: 20px;">Containers</b></h5>
						<p style="font-size: 12px;">A single place for your team to manage Docker images and decide who can see and access your images.</p>
						<button type="button" class="btn btn-default btn-sm" style="border-radius: 4px;">Learn More</button><br><br>
					</div>
				</div>
			</div>
		</div>	



	<hr style="width:90%; background-color: white;">

	<div class="footer" style="background-color: white;">
		
		<nav class="navbar">
			<p class="navbar-text">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&copy; 2020 GitHub, Inc.</p>
		  	<ul class="nav navbar-nav">
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Terms</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Privacy</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Security</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Status</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Help</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Contact GitHub</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Pricing</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp API</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Training</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp Blog</a></li>
		    	<li><a href="#" style="color: blue;">&nbsp&nbsp&nbsp&nbsp About</a></li>
		  	</ul>
		</nav>
		
	</div>
</body>
</html>
