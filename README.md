<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,initial-scale=1">
	<title>Menu</title>
	<style >
		*{
			box-sizing: border-box;	

		}
		h1{
			margin-bottom: 15px;
			text-align: center;
			font-style: italic;
			font-family: Comic Cans MS;
			color: black;
		}
		section{
			position: relative;
			left: 150px;
			font-style: italic;
			font-size: 25px;
			color: #5F9EA0;
		}

		p{
			border:2px solid black;
			background-color: #DEB887;
			width:90%;
			height:150px;
			font-family: cursive;
			margin-right: auto;
			margin-left: auto;
			color: white;
			overflow: auto;
		}
		.row{
			width: 100%;
		}
		@media (min-width: 992px){
			.col-lg-1,.col-lg-2,.col-lg-3{
				float: left;
				border: 2px;
			}
			.col-lg-1{
				width: 30%;
			}
			.col-lg-2{
				width:30%;
			}
			.col-lg-3{
				width: 30%
			}
		}
 		@media(min-width: 768px) and (max-width: 991px){
 			.col-md-1,.col-md-2,.col-md-3{
 				float:left;
 				border:2px;
 			}
 			.col-md-1{
 				width:50%;
 			}
 			.col-md-2{
 				width:50%;
 			}
 			.col-md-3{
 				width:100%;
 			}
 		}
 		@media(max-width: 767px){
 			.col-sa-1,.col-sa-2,.col-sa-3{
 				float: left;
 				border:2px;
 			}
 			.col-sa-1{
 				width:100%;
 			}
 			.col-sa-2{
 				width:100%;
 			}
 			.col-sa-3{
 				width:100%;
 			}
 		}
 		body{
 			background-color: pink;
 			padding-left: 15px;
 			padding-right: 15px;
 		}

	</style>
</head>
<body>
	<h1>Our Menu</h1>
	<div class="row" >
		
		<div class="col-lg-1 col-md-1  col-sa-3"><section>Chicken</section><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit error quis ab perspiciatis eos inventore recusandae iste itaque numquam facilis, tenetur. Doloribus officiis quae facilis, nisi, ex similique. Animi, perferendis. </p></div>
		<div class="col-lg-1 col-md-1  col-sa-3"><section>Beef</section><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit error quis ab perspiciatis eos inventore recusandae iste itaque numquam facilis, tenetur. Doloribus officiis quae facilis, nisi, ex similique. Animi, perferendis. </p></div>
		<div class="col-lg-1 col-md-1 col-md-3 col-sa-3"><section>Pizza</section><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit error quis ab perspiciatis eos inventore recusandae iste itaque numquam facilis, tenetur. Doloribus officiis quae facilis, nisi, ex similique. Animi, perferendis. </p></div>

</div>
</body>
</html>
