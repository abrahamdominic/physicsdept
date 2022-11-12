<!DOCTYPE html>
<html>
<head>
	<title>Gallery</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>
<style>
	
.hovereffects{
   width: 100%;
   height: 100%;
   overflow: hidden;
   position: relative;
   text-align: center;
   cursor: default;
   margin-bottom: 10px;
}

.hovereffects .overlay{
	width: 100%;
	height: 100%;
	position: absolute;
	overflow: hidden;
	top: 0;
	left: 0;
	opacity: 0;
	background-color: rgba(0,0,0,0.5);
	-webkit-transition: all 0.4s ease-in-out;
	transition: all 0.4s ease-in-out
}

.hovereffects img{
	display: block;
	position: relative;
	-webkit-transition: all .4s linear;
	transition: all .4s linear;
}

.hovereffects h2{
	text-transform: uppercase;
	color: #fff;
	text-align: center;
	position: relative;
	font-size: 17px;
	background: rgba(0,0,0,0.6);
	-webkit-transform: translateY(-100px);
	-ms-transform: translateY(-100px);
	transform: translateY(-100px);
	-webkit-transition: all .2s ease-in-out;
	transition: all .2s ease-in-out;
	padding: 10px;
}

.hovereffects a.info{
	text-decoration: none;
	display: inline-block;
	text-transform: uppercase;
	color: #fff;
	border:1px solid #fff;
	background-color: transparent;
	opacity: 0;
	filter: alpha(opacity=0);
	-webkit-transition: all .2s ease-in-out;
	transition: all .2s ease-in-out;
	margin: 50px 0 0;
	padding: 7px 14px;
}

.hovereffects a.info:hover{
	box-shadow: 0 0 5px #fff;

}

.hovereffects:hover img{
	-ms-transform: scale(1.2);
	-webkit-transform: scale(1.2);
	transform: scale(1.2);
}

.hovereffects:hover .overlay{
	opacity: 1;
	filter: alpha(opacity=100);
}

.hovereffects:hover h2, .hovereffects:hover a.info{
	opacity: 1;
	filter: alpha(opacity=100);
	-ms-transform: translateY(0);
	-webkit-transform: translateY(0);
	transform: translateY(0);
}

.hovereffects:hover a.info{
	-webkit-transition-delay: .2s;
	transition-delay: .2s;
}











</style>


<body>

<h2 class="text-center" style="font-family: monospace;">Hover Effect Gallersy</h2>
<br><br>
<div class="container">
<div class="row">

<div class="col-md-4 col-sm-6 col-xs-12">
	<div class="hovereffects">
		<img src="img1.jpg" height="300px" width="100%" alt="images">
		<div class="overlay">
			<h2>Awesome Temples</h2>
			<a class="info" href="#">more info</a>
		</div>
	</div>

</div>


<div class="col-md-4 col-sm-6 col-xs-12">
	<div class="hovereffects">
		<img src="img2.jpg" height="300px" width="100%" alt="images">
		<div class="overlay">
			<h2>Mountain</h2>
			<a class="info" href="#">more info</a>
		</div>
	</div>

</div>




<div class="col-md-4 col-sm-6 col-xs-12">
	<div class="hovereffects">
		<img src="img3.jpg" height="300px" width="100%" alt="images">
		<div class="overlay">
			<h2>Sunset</h2>
			<a class="info" href="#">more info</a>
		</div>
	</div>

</div>



<div class="col-md-4 col-sm-6 col-xs-12">
	<div class="hovereffects">
		<img src="img4.jpg" height="300px" width="100%" alt="images">
		<div class="overlay">
			<h2>Awesome Building</h2>
			<a class="info" href="#">more info</a>
		</div>
	</div>

</div>



<div class="col-md-4 col-sm-6 col-xs-12">
	<div class="hovereffects">
		<img src="img5.jpg" height="300px" width="100%" alt="images">
		<div class="overlay">
			<h2>Nature</h2>
			<a class="info" href="#">more info</a>
		</div>
	</div>

</div>



<div class="col-md-4 col-sm-6 col-xs-12">
	<div class="hovereffects">
		<img src="img6.jpg" height="300px" width="100%" alt="images">
		<div class="overlay">
			<h2>Bowl</h2>
			<a class="info" href="#">more info</a>
		</div>
	</div>

</div>









</div>
</div>





</body>
</html>