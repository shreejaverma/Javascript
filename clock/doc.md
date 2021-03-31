<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="500" height="500"
style="border:1px solid #c3c3c3;">
Your browser does not support the canvas element.
</canvas>

<script>
var canvas = document.getElementById("myCanvas");
var ctx = canvas.getContext("2d");
ctx.beginPath();
ctx.arc(250,250,150,0,2*Math.PI);
ctx.stroke();
ctx.fillStyle= "#4a3933";
ctx.fill();
ctx.font= "30px Arial";
ctx.textAlign = "center";
ctx.fillStyle = "white";
ctx.fillText("•",250,255);
ctx.fillText("6", 250, 390);
ctx.fillText("8", 140, 320);
ctx.fillText("7", 180, 370);
ctx.fillText("9", 120, 255);
ctx.fillText("10", 180, 150);
ctx.fillText("11", 140, 190);
ctx.fillText("12", 250, 130);
ctx.fillText("1", 320, 150);
ctx.fillText("2", 360, 190);
ctx.fillText("3", 380, 255);
ctx.fillText("5", 330, 370);
ctx.fillText("4", 370, 320);
</script>

</body>
</html>