# animation-circle
html code
<html>
<head>
<meta charset="utf-8">
<title>анимированый круг</title>
<script>
function circle()
{
	var canvas = document.getElementById('circle');
	var obCanvas =canvas.getContext('2d');
	
	obCanvas.beginPath();
	obCanvas.arc(150,75,50,0,2*Math.PI,false);
	obCanvas.fillStyle = 'green'; 
	obCanvas.fill();
	obCanvas.lineWidth = 1;
	obCanvas.strokeStyle = 'green';
	obCanvas.stroke; 
	}
</script>
</head>

<body onLoad = "circle()">
	
<canvas id = "circle()"></canvas>
</body>

</html>
