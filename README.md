<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
  <link rel="stylesheet" type="text/css" href="CSS/paris.css">
  <style>
  
  body {
	background-color: #f8f7f7;
  }
  
  .navbar-top {
	background-color: #9d122f;
  }
  
  .navbar-brand {
	color: white;
	font-family: Verdana, Geneva, sans-serif;
	font-size: 18px;
  }

  .dropdown-toggle {
	color: white;
	font-family: Verdana, Geneva, sans-serif;
	font-size: 18px;
  }

  .location {
	color: white;
	font-family: Verdana, Geneva, sans-serif;
	font-size: 14px;
  }
  
  .dropdown-toggle2 {
	color: white;
	font-family: Verdana, Geneva, sans-serif;
	font-size: 14px;
  }
	
  div.container-fluid {
	background-color: #85041f;
	color: white;
	font-family: Verdana, Geneva, sans-serif; 
	font-size: 11px;
	text-align: center;
  }
  	
  .jumbotron {
	position: relative;
    background: url("CSS/Images/louvre.jpg") center center;
    width: 100%;
    height: 450px;
    background-size: cover;
    overflow: hidden;
	}
	
  p.txt1 {
	color: #ffd22a;
	text-align: center;
	font-family: "Comic Sans MS", cursive, sans-serif;
	font-size: 18px;
  }
  
  h1.tagline {
	color: white;
	text-align: center;
	font-family: "Comic Sans MS", cursive, sans-serif;
	font-size: 42px;
  }
  
  .btn-xs.round {
	border-radius: 8px;
	font-family: Verdana, Geneva, sans-serif;
	color: #9d122f;
	padding: 10px 26px;
	font-size: 9px;
  }
	
  .box {
	text-align: center;
	font-family: Verdana, Geneva, sans-serif;
	font-size: 14px;
	margin-left: 22%;
	margin-right: 22%;
	line-height: 25px;
  }

.imagetitle {
	text-align: center;
}

td {
	padding: 25px
}

img {
	position: absolute;
	z-index: -1;
}

.post-content {
	color: white;
	font-family: Verdana, Geneva, sans-serif;
	text-align: center;
	font-size:12px;
}

footer {
	bottom: 0px;
}

ul.footernav {
	color: red;
	top:100px;
}

  </style>
</head>
<body>

<nav class="nav navbar-top">
	<div>
		<div class="navbar-header">
			<a class="navbar-brand"><strong>BIG</strong>BUS</a>
		</div>
	<ul class="nav navbar-nav">
		<li class="dropdown">
			<a class="dropdown-toggle" data-toggle="dropdown"><strong>PARIS</strong>
			<span class="glyphicon glyphicon-menu-down"></span></a>
		</li>
	</ul>
	<ul class="nav navbar-nav navbar-right">		
		<li>
			<a class="location" href="#"><span class="glyphicon glyphicon-map-marker"></span>FIND A BUS STOP</a>
		</li>
		<li class="dropdown">
			<a span class="dropdown-toggle2" data-toggle="dropdown">ENG / GPB £
			<span class="glyphicon glyphicon-menu-down"></span></a>
		</li>	
	</ul>
	</div>
</nav>

<nav class="nav navbar-default">
	<div class="container-fluid">
	<ul class="nav navbar-nav">
		<li><a href="#">OUR TOURS</a></li>
		<li><a href="#">ROUTES & TIMES</a></li>
		<li><a href="#">TICKETS & PASSES</a></li>
		<li><a href="#">DISCOVER PARIS</a></li>
		<li><a href="#">HELP</a></li>
	</ul>
	<ul class="nav navbar-nav navbar-right">
		<li><a href="#" class="btn btn-warning" role="button">BUY TICKET</a></li>	
	</ul>	
	</div>
</nav>

<div class="jumbotron">
	<div class="container"></br></br></br></br></br></br>
		<p class="txt1"><strong>Paris bus tours</strong></p>
		<h1 class="tagline"><strong>Explore the City of Love</strong></h1></br>
	</div>
	<div class="text-center">
		<button type="button" a href="#" class="btn btn-default btn-xs round"><strong>DISCOVER PARIS TOURS</strong></button>
	</div>	
</div>



<div class="box">
<p>
  Our Paris Bus Tours provide the perfect introduction to the world's most romantic city. Hop on and off the bus when
 you wish to explore the city's sights or to stroll hand in hand along the River Seine.</p> 
</br>
</br>
</div>
	<p class="imagetitle"><strong>Why choose our sightseeing bus tours?</strong></p>

<table>
          <tr>
	<td><div ="img1">
		<img src="CSS/Images/image1.jpg" class="img-responsive" alt="Bus image" style="width:204px;height:140px;">
	<div class="post-content"		
		<h2>Hop-on, Hop-off</h2>
		<p> As many times as you choose</p>
	</div>
	</div></td>
	<td><div="img2">
		<img src="CSS/Images/image2.jpg" class="img-responsive" alt=Eiffel tower" style="width:204px;height:140px;">
	<div class="post-content"		
		<h3>Our Amazing Routes</h3>
		<p> See Paris by day and night</p>
	</div>
	</div></td>
	<td><div="img3>
		<img src="CSS/Images/image3.jpg" class="img-responsive" alt="River Seine" style="width:204px;height:140px;">
	<div class="post-content"		
		<h4>Free River Cruise</h4>
		<p> One ticket, two experiences</p>
	</div>
	</div></td>
	<td><div="img4">
		<img src="CSS/Images/image4.jpg"  class="img-responsive" alt="Louvre" style="width:204px;height:140px;">
	<div class="post-content"		
		<h5>Live Guides</h5>
		<p>With renowed local knowledge</p>
	</div>
	</div></td>
          </tr>
</table>

<footer>
	<div>
	<ul   class="footernav">
		<li><a href="#"><stong>Big Bus Tours</strong></a></li>
		<li><a href="#">About Big Bus Tours</a></li>
		<li><a href="#">Private Hires</a></li>
		<li><a href="#">Recruitment</a></li>
		<li><a href="#">Press Enquiries</a></li>
		<li><a href="#">Affiliate</a></li>
	</ul>
	</div>
</footer>

</body>
</html>
