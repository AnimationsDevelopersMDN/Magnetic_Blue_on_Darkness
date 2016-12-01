# Magnetic_Blue_on_Darkness
" Magnetic Blue on Darkness" is a new CSS animation developed by Rober Villar, from Software RVG. This is a basic css animation with transformation properties, rotate and translate, transform. Added as background a simple dark black for getting a big "space effect", with easy construction. More later added a two GRADIANT SVG COLORS. Programming runtimes for explaining snippet.  All properties are changing rapidly, getting different effects immediately, It can be done orbit or stay in place. 

<meta name="generator" content="Software RVG HTML Editor (www.softwarervg.com)">
    <meta name="dcterms.created" content="sa., 03 ago. 2016 01:25:28 GMT">
    <meta name="Software RVG Designs...designing Future" content="css,,development,by;Software-RVG">
    <meta name="keywords" content="css,,Software RVG,3D animation,designs,creative work,artistic work">
    <title>css  animation "magnetic blue on darkness"</title>
    
    
_____________________________________________________________________________________________________________________________

                                                   HTML ANIMATION 

____________________________________________________________________________________________________________________________
    
<div class="view">
  <div class="plane main">
    <div class="circle"></div>
    <div class="circle"></div>
    <div class="circle"></div>
    <div class="circle"></div>
    <div class="circle"></div>
    <div class="circle"></div>
  </div>
</div>
<html><head></head><body><div id="svg-text"><canvas width="800" height="100" style="display: block; touch-action: none; -webkit-user-select: none; -webkit-tap-highlight-color: rgba(0, 24, 88, 0.8);
width: 800px;height: 100px;"></canvas></div>

<style>
      
______________________________________________________________________________________________________________________________

                                                       SET STYLE
                                                       
______________________________________________________________________________________________________________________________
/* Main styles */
@import url(http://fonts.googleapis.com/css?family=Open+Sans:800);

.text {
  fill: url(#gr-radial);
}

/* Other styles */
body {
  min-height: 450px;
  height: 100vh;
  margin: 0; }
body sgv {
  
  background-size: .1em 100%;
  font: 1.1em/1 Open Sans, Impact;
  text-transform: uppercase;
  margin: 0;
}

body text {

  background-size: .1em 100%;
  font: 1.1em/1 Open Sans, Impact;
  text-transform: uppercase;
  margin: 0;
}

svg {
  position: absolute;
  width: 100%;
  height: 140%;
  margin-top:-40px;
}


    </style>
    
    
    
_____________________________________________________________________________________________________________________________

                                                      SVG ANIMATION
                                                     
_____________________________________________________________________________________________________________________________

<div class:"text"="">

<svg viewBox="0 0 600 300">
 <!-- Gradient -->
  <radialGradient id="gr-radial" cx="50%" cy="50%" r="70%">
    <!-- Animation for radius of gradient -->
    <animate attributeName="r" values="0%;150%;100%;0%" dur="3s" repeatCount="indefinite"></animate>
    <!-- Animation for colors of stop-color -->
    <stop stop-color="#FFFf00" offset="0">
      <animate attributeName="stop-color" values="#0000FF;#ffff00;#00FF00;#FF0000;#00FF00;#0000FF;#FFFF00;#00FF00;#FF0000;#0000FF;#FFFF00;#FF0000" dur="20s" repeatCount="indefinite"></animate>
    </stop>
    <stop stop-color="rgba(55,55,55,0)" offset="100%"></stop>
  </radialGradient>
  
 
  <!-- Text -->
  <text text-anchor="middle" x="50%" y="45%" dy=".35em" class="text">
    © SOFTWARE RVG DESIGNS
 </text>
  
 </svg></div></body></html>
 <div class:"text"="">

<svg viewBox="0 0 600 300">
 <!-- Gradient -->
  <radialGradient id="gr-radial" cx="50%" cy="50%" r="70%">
    <!-- Animation for radius of gradient -->
    <animate attributeName="r" values="0%;150%;100%;0%" dur="2s" repeatCount="indefinite"></animate>
    <!-- Animation for colors of stop-color -->
    <stop stop-color="#FFFf00" offset="10">
      <animate attributeName="stop-color" values="#0000FF;#ffff00;#00FF00;#FF0000;#00FF00;#0000FF;#FFFF00;#00FF00;#FF0000;#0000FF;#FFFF00;#FF0000" dur="20s" repeatCount="indefinite"></animate>
    </stop>
    <stop stop-color="rgba(55,55,55,0)" offset="100%"></stop>
  </radialGradient>
  
 
  <!-- Text -->
  <text text-anchor="middle" x="50%" y="55%" dy=".35em" class="text">
   " Magnetic blue on Darkness "
 </text>
  
 </svg></div></body></html>
 
 
_____________________________________________________________________________________________________________________________

                                                   CSS ANIMATION STYLE

_____________________________________________________________________________________________________________________________

body {
  min-height: 450px;
  height: 100vh;
  margin: 0;
  background: black;
}

.view {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  -webkit-perspective: 400;
          perspective: 400;
}

.plane {
  width: 250px;
  height: 250px;
  -webkit-transform-style: preserve-3d;
          transform-style: preserve-3d;
}
.plane.main {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  margin: auto;
  -webkit-transform: rotateX(60deg) rotateZ(-30deg);
          transform: rotateX(60deg) rotateZ(-30deg);
  -webkit-animation: rotate 20s infinite linear;
          animation: rotate 20s infinite linear;
}
.plane.main .circle {
  width:200px;
  height:200px;
  position: absolute;
  -webkit-transform-style: preserve-3d;
          transform-style: preserve-3d;
  border-radius: 25%;
  box-sizing: border-box;
  box-shadow: 0 0 80px  #00FFFF, inset 0 0 30px #0000FF;
	
}
.plane.main .circle::before, .plane.main .circle::after {
  content: "";
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  margin: auto;
  width: 5%;
  height: 15%;
  border-radius: 20%;
  background:;
  box-sizing: border-box;
  box-shadow: 0 0 6px 6px #00ff00;
}
.plane.main .circle::before {
  -webkit-transform: translateZ(-90px);
          transform: translateZ(-90px);
}
.plane.main .circle::after {
  -webkit-transform: translateZ(90px);
          transform: translateZ(90px);
}
.plane.main .circle:nth-child(1) {
  -webkit-transform: rotateZ(72deg) rotateX(63.435deg);
          transform: rotateZ(72deg) rotateX(63.435deg);
}
.plane.main .circle:nth-child(2) {
  -webkit-transform: rotateZ(144deg) rotateX(63.435deg);
          transform: rotateZ(144deg) rotateX(63.435deg);
}
.plane.main .circle:nth-child(3) {
  -webkit-transform: rotateZ(216deg) rotateX(63.435deg);
          transform: rotateZ(216deg) rotateX(63.435deg);
}
.plane.main .circle:nth-child(4) {
  -webkit-transform: rotateZ(288deg) rotateX(63.435deg);
          transform: rotateZ(288deg) rotateX(63.435deg);
}
.plane.main .circle:nth-child(5) {
  -webkit-transform: rotateZ(360deg) rotateX(63.435deg);
          transform: rotateZ(360deg) rotateX(63.435deg);
}

@-webkit-keyframes rotate {
  0% {
    -webkit-transform: rotateX(0) rotateY(0) rotateZ(0);
            transform: rotateX(0) rotateY(0) rotateZ(0);
  }
  100% {
    -webkit-transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg);
            transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg);
  }
}

@keyframes rotate {
  0% {
    -webkit-transform: rotateX(0) rotateY(0) rotateZ(0);
            transform: rotateX(0) rotateY(0) rotateZ(0);
  }
  100% {
    -webkit-transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg);
            transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg);
  }
}
