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

		div{
			border-radius: 5px;
		}
		.image-small{
			width: 25px;
		}
		.img-margin{
			margin: auto;
		}

		* {box-sizing: border-box;}

		.container-fluid {
			  overflow: hidden;
			  background-color: black;
			}

		.container-fluid a {
			  float: left;
			  display: block;
			  color: white;
			  text-align: center;
			  padding: 14px 16px;
			  text-decoration: none;
			  font-size: 14px;
			}

		.container-fluid a.hover {
		  background-color: black;
		  color: grey;
		}

		.container-fluid .search-container {
		  float: left;
		}

		.container-fluid .search-container button {
		  float: right;
		  padding: 6px 10px;
		  margin-top: 10px;
		  margin-right: 16px;
		  background: black;
		  font-size: 14px;
		  border: none;
		  cursor: pointer;
		}

		@media screen and (max-width: 600px) {
		  .container-fluid .search-container {
		    float: none;
		  }
		  .container-fluid a, .container-fluid input[type=text], .container-fluid .search-container button {
		    float: none;
		    display: block;
		    text-align: left;
		    width: 100%;
		    margin: 0;
		    padding: 14px;
		    background-color: black;
		  }
	</style>

	<style>

		.subnav {
		  overflow: hidden;
		  background-color: white;
		}

		.subnav a {
		  float: left;
		  display: block;
		  color: black;
		  text-align: center;
		  padding: 14px 16px;
		  text-decoration: none;
		  font-size: 14px;
		  border-bottom: 3px solid transparent;
		  margin-top: 50px;
		}

		.subnav a:hover {
		  border-bottom: 2px solid grey;
		}

		.subnav a.active {
		  border-bottom: 2px solid red;
		}
	</style>-->
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
</body>
