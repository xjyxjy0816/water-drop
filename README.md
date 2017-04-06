<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style>
		@keyframes ani{
			from{
				transform: rotate(0deg)
			}
			to{
				transform: rotate(360deg);
			}
		}

		#box{
			width: 200px;
			height: 200px;
			margin:  20px auto;
			border-radius: 98px 96px 89px 91px;
			box-shadow: -2px 0px 3px red,2px 0px 3px yellow;
			animation: 3s ani linear infinite;
		}
	</style>
</head>
<body>
	<div id="box"></div>
</body>
</html>
