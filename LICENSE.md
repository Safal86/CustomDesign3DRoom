<!DOCTYPE html>
<html>
<head>
  <title></title>
<style type="text/css">
  .main{ width:1366px; max-width:1366px; padding:0; margin:0; display:block;}
  .container {width:1300px; height:50px; position: relative; -webkit-perspective:1100; max-width:1366px;}
  #cube {perspective:600px; width:80%; height: 100%; position: absolute;-webkit-transform-style: preserve-3d;}

/*#cube .front { -webkit-transform: rotateY(0deg) translateZ(100px); }*/
#cube .back { -webkit-transform: translateZ(-100px); }
#cube .bottom { -webkit-transform: rotateX(90deg) translateZ(-500px); }

#cube .left { -webkit-transform: rotateY(-90deg) translateZ(100px); }

#cube .right { -webkit-transform: translateZ(100px) rotateY(-0deg); }

/*#cube .top { -webkit-transform: rotateX(90deg) translateZ(100px); }*/


#cube figure {width:200px; height:200px; display: block; position: absolute; border: none; max-width:1200px;}
img{ max-width:1024px; }
</style>
</head>
<body>
<div class="main">
<section class="container">
  <div id="cube">
    <figure class="back"><img src="cloud.jpg"></figure>
    <figure class="bottom"><img src="Dance.jpg"></figure>
    <figure class="left"><img src="Camaleon.jpg"></figure>
    <figure class="right"><img src="LifeStock.jpg"></figure>
  </div>
</section>
</div>
</body>
</html>
