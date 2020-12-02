# first-game
I'm just making a simple game with html, css, and java where the player is a square and they have to avoid rectangles
code so far but i cant get it to work
<!Doctype html>
<html>
	<head>
		<title> game </title>
		<script src="script.js"></script>
		<link rel="stylesheet" type="text/css" href="style.css">
	</head>
<body>
	<canvas id="stage" width="400" height="400"></canvas>
	<script>
		var canvas = document.getElementById ('stage');
		var ctx = canvas.getcontext('2d');
	
		function rect((x,y,w,h,color) {
			ctx.beginPath();
			ctx.rect(x,y,w,h);
			ctx.fillStlye = color;
			ctx.fill();
			ctx.closepath();
		}
	rect(100,200,100,100,"#0000ff");
	</script>
</body>
</html>
