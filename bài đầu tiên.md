<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<link href="style2.css" rel="stylesheet" type="text/css">
<link rel="stylesheet" href="jquery-ui.css">
<script src="jquery-1.10.2.js"></script>
<script src="jquery-ui.js"></script>
<script>
	$(function() {
    $( ".datepicker" ).datepicker();
  });
  </script>
<title>bai2</title>
</head>
<body>
	<div class="wrap">
		<div class="header">
			<div class="logo">
				<p>hotel<span class="yellow"> deluxe</span></p>
			</div>
			<div class="slogan">
				<p>Hotel & Motel theme<p>
			</div>
			<div class="menu">
				<ul>
					<li><a href="#">start</a></li>
					<li><a href="#">facilities</a></li>
					<li><a href="#">restaurant</a></li>
					<li><a href="#">conference</a></li>
					<li><a href="#">bookings</a></li>
					<li><a href="#">contact us</a></li>
				</ul>
			</div>
			<div style="clear:both">
			</div>
		</div>
		<div class="slider">
			<p>Hello,You've Reached</p>
			<hr class="top">
			<h1>HOTEL DELUXE</h1>
			<hr class="bottom">
			<ul>
				<li><a href="">HOTEL   <span style=" color:white">-</span></a></li>
				<li><a href="">SPA SALOON  </a></li>
				<li><a href=""><span style=" color:white">-</span>  FINE DINING</a></li>
			</ul>
		</div>
		<div class="booking">
			<div class="checkin">
				<p class="lable"> Arriva</p>
				<input type="text" class="datepicker date" id="datepicker" >
			</div>
			<div class="checkout">
				<p class="lable"> Departure</p>
				<input type="text" class="datepicker date" id="datepicker2">
			</div>
			<div class="Room">
				<p class="lable-room"> Room Type</p>
					<form action="#">
						<select>
							<option selected="selected">None</option>
							<option value="Single">Single</option>
							<option value="Double">Double</option>
						</select>
					<form>
			</div>
			<button type="button" class="view-prices">View Prices
			</button>
			<div style="clear:both">
			</div>
		</div>
		<div class="content">
			<img src="bookA.png">
			<div class="slider-package">
				<a href=" " class="back">
				</a>
				<div class="list-circle">
				   <ul>
						<li id="circle">
							<div class="content-circle">text
							</div>
						</li>
						<li id="circle">
							<div class="content-circle">text
							</div>
						</li>
						<li id="circle">
							<div class="content-circle">text
							</div>
						</li>
				   </ul>
				 </div>
				<a href=" " class="next">
				</a>
			</div>
			<div style="clear:both">
			</div>
			<div class="Our-room">
				<p class="title">Our Room Type</p>
				<div class="list-room">
					<ul>
						<li class="detail-room">
							<p class="image-room"></p>
						</li>
						<li class="detail-room">
							<p class="image-room"></p>
						</li>
						<li class="detail-room">
							<p class="image-room"></p>
						</li>
						<li class="detail-room">
							<p class="image-room"></p>
						</li>
						<li class="detail-room">
							<p class="image-room"></p>
						</li>
						<li class="detail-room">
							<p class="image-room"></p>
						</li>
					</ul>
				</div>
				<div class="footer-room">
					<div class="your-picture">
					</div>
				</div>
			</div>
			
		</div>
		<div class="footer">
				</div> 
	</div>
</body>
</html>
