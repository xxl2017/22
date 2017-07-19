<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>适配的左中右布局</title>
	<style type="text/css">
		*{
			padding: 0;
			margin: 0;
		}
		html,body{
			height: 100%;
		}
		div{
			height: 100%;
		}
		.left{
		    background-color: pink;
		    width: 200px;
		    position: absolute;
		    left: 0;
		    top: 0;
		}
		.center{
			padding-left: 200px;
			padding-right: 200px;
			width: 100%;
			box-sizing: border-box;
		}
		.center-inner{
			background-color: blue;
		}
		.right{
			background-color: pink;
			width: 200px;
			position: absolute;
			right: 0;
			top: 0;
		}
	</style>
</head>
<body>
	<div class="left">左</div>
	<div class="center">
		<div class="center-inner">中</div>
	</div>
	<div class="right">右</div>
</body>
</html>
