# canvasOnYoutube1stTimeBern
<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>

  <title>HTML5 Canvas</title>
  <style>
    canvas {
      border: #000000 1px solid;
    }
  </style>
  <script type="text/javascript">
    var c = document.getElementById('myCanvas');
    var ctx;

    function init() {
      c = document.getElementById('myCanvas');
      ctx = c.getContext('2d');
      draw();

    }

    function draw() {
ctx.fillStyle="red";
ctx.fillRect(30,30,50,50);

    }
  </script>
</head>

<body onload="init()">
  <canvas id="myCanvas" width="400" height="150"></canvas>
  <p>Your browser does not have the canvas feature if you cannot see the image</p>
</body>

</html>
