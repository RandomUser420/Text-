# Text-
Text()
<html>
  <head>
    <script src="p5.min.js"></script>
    <script src="p5.gui.js"></script>
    <script src="quicksettings.js"></script>
    <script src="p5.dom.js"></script>
    <style>
      body {
      margin: 0;
      padding: 0;
      }
    </style>
  </head>
  <body>
    <script>
      var w = window.innerWidth;
      var h = window.innerHeight;
      function setup() {
        createCanvas(w,h);
      }
      function draw() {
        textSize(50);
        text(" there is a dinosaur. it is brown. It took one shower", 200, 200, 200, 500);
        fill("blue");
      }
    </script>
  </body>
</html>
