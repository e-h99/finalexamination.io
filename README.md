# finalexamination.io
<!DOCTYPE html>
<html>

<head>
	
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>CIVENG 2O04 Final Exam</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <style type="text/css">
    	img{display: block; margin-left: auto; margin-right: auto;}
    </style>

    <link rel="stylesheet" media="screen" href="https://fontlibrary.org/face/cmu-serif" type="text/css"/>

    <style type="text/css">
h1 { 
  display: block;
  font-size: 1.5em;
  margin-top: 0.67em;
  margin-bottom: 0em;
  margin-left: 0;
  margin-right: 0;
  font-weight: bold;
}

h2 {
  display: block;
  font-size: 1.5em;
  margin-top: 0.45em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
  font-weight: bold;
}

h3 {
  display: block;
  font-size: 1.5em;
  margin-top: 0.67em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
  font-weight: bold;
}

h4 {
  display: block;
  font-size: 1.3em;
  margin-top: 0.67em;
  margin-bottom: 3em;
  margin-left: 0;
  margin-right: 0;
  font-weight: bold;
}

h5 {
  display: block;
  font-size: 1em;
  margin-top: 0.67em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
  font-weight: bold;
}

.preamble h1 {
  text-align: center;
  margin-bottom: 1;
}
.preamble h2 {
  line-height: 0px;
  text-align: center;
  margin-bottom: 1;
  margin-top: 1;
}
.preamble h3 {
  line-height: 0px;
  text-align: center;
  margin-bottom: 1;
  margin-top: 1;
}
.preamble h4 {
  line-height: 0px;
  text-align: center;
  margin-bottom: 2;
  margin-top: 1;
}
.preamble h5 {
  line-height: 0px;
  text-align: center;
  margin-bottom: 0;
  margin-top: 2;
}

    </style>

    <style type="text/css">
    	h6 { 
  display: block;
  font-size: 1em;
  margin-top: 0.67em;
  margin-bottom: 0em;
  margin-left: 20%;
  margin-right: 0;
  font-weight: bold;
}

.instructions h6 {
  margin-bottom: 1;
}

.h7{
    font-size: 1em;
    margin-bottom: 0;
    margin-left: 20%;
    margin-right: 0;
 }

 .h8{
    font-size: 1em;
    margin-bottom: 0;
    margin-left: 20%;
    margin-right: 0;
 }

.h9{
    font-size: 1em;
    margin-bottom: 0;
    margin-left: 20%;
    margin-right: 0;
 }

 .h10{
    font-size: 1em;
    margin-bottom: 0;
    margin-left: 20%;
    margin-right: 20%;
 }

 .h11{
    font-size: 1em;
    font-weight: bold;
    margin-left: 20%;
 }

</style>


	<style>
	.content    { width: 60%;
	    text-align: justify;
		margin-left:17%;}
		
	.center {
	  display: block;
	  margin-left: 0%;
	  margin-right: auto;
	}

	.center60 {
	  display: block;
	  margin-left: 20%;
	  margin-right: auto;
	}
	
	.center40 {
	  display: block;
	  margin-left: 30%;
	  margin-right: auto;
	}

	.yeet {
	  display: block;
	  margin-left: 0%;
	  margin-right: auto;
	}
    ol {
      list-style: none;
       counter-reset: list-counter;
    }
    ol li {
      counter-increment: list-counter;
    }
    ol li::before {
      content: "Problem " counter(list-counter);
      font-weight: bold;
      font-size: 110%;
    }
	</style>


<script type='text/javascript'>
var isCtrl = false;
document.onkeyup=function(e)
{
if(e.which == 17)
isCtrl=false;
}
document.onkeydown=function(e)
{
if(e.which == 123)
isCtrl=true;
if (((e.which == 85) || (e.which == 65) || (e.which == 88) || (e.which == 67) || (e.which == 86) || (e.which == 2) || (e.which == 3) || (e.which == 123) || (e.which == 83)) && isCtrl == true)
{
alert('This is Function Disabled');
return false;
}
}
var isNS = (navigator.appName == "Netscape") ? 1 : 0;
if(navigator.appName == "Netscape") document.captureEvents(Event.MOUSEDOWN||Event.MOUSEUP);
function mischandler(){
    alert('This is Function Disabled');
return false;
}
function mousehandler(e){
var myevent = (isNS) ? e : event;
var eventbutton = (isNS) ? myevent.which : myevent.button;
if((eventbutton==2)||(eventbutton==3)) return false;
}
document.oncontextmenu = mischandler;
document.onmousedown = mousehandler;
document.onmouseup = mousehandler;

function killCopy(e){
return false
}
function reEnable(){
return true
}
document.onselectstart=new Function ("return false")
if (window.sidebar){
document.onmousedown=killCopy
document.onclick=reEnable
}

</script>
</head>

<style>
body {
  font-family: "CMUSerifRoman";
}
</style>
<body>
<div class="preamble">
  <h1 align="center">MCMASTER UNIVERSITY</h1>
  <h2 align="center">FINAL EXAM, April 2020</h2>
  <h3 align="center">CIVENG 2O04 - Fluid Mechanics</h3>
  <h4 align="center">Duration: 2.5 hours</h4>
  <h5 align="center">Instructor: Dr. Benzhong Zhao</h5>
</div>
<br><br>
<hr>
<p class="h10"> THIS EXAMINATION PAPER INCLUDES 7 QUESTIONS. YOU ARE RESPONSIBLE FOR ENSURING THAT YOUR COPY OF THE PAPER IS COMPLETE. BRING ANY DISCREPANCY TO THE ATTENTION OF YOUR INVIGILATOR. </p>
<br>
<div class="instructions">
	<h6 align="margin-left">Special Instructions:</h6>
	<p class="h7"> Use of Casio FX-991 MS or MS Plus calculator only is allowed. </p>
	<p class="h8"> Please answer each question on separate sheets of paper and upload all the pages onto Avenue as one single PDF file. </p>
	<p class="h9"> GOOD LUCK! </p>
</div>
<hr>
<script>
    p1Function();

    function p1Function() {
        classID = prompt("Please enter the second last digit of your class ID", "1");
    }

    i = Math.floor(classID/25)
</script>
<ol class="content">
    <li>
        <div class="question">
            <p id="p1"></p>

            <script>
            var d=[10,20,30,40,50];
            var R=[1,2,3,4,5];
            var h=[10,20,30,40,50];

            document.getElementById("p1").innerHTML=("An L-shaped aquarium consists of 2 cylindrical volumes that are filled with water (see figure below). You are given the diameter of the vertical cylinder d = "+ d[i] +" m, and the radius of the horizontal cylinder R = " + R[i] + " m. The horizontal cylinder is sealed on one end with a semi-spherical cap. <br><br> <br>Given the height of the vertial cylinder h = " + h[i] + " m, find the total horizontal resultant force F on the semi-spherical cap.")
            </script>

            <table class="image">
            <caption align="bottom"> L-shaped aquarium sealed by semi-spherical cap.</caption>
            <tr><td><img src="https://i.ibb.co/FxLgbhb/fig1.png" class="center" width=125%></td></tr>
            </table><hr>
        </div>
    </li>
    <li>
        <div class="question"><p id="p2"></p>
            <script>
            
            var b=[10,20,30,40,50];
            var L=[10,20,30,40,50];
            var theta=[2,4,6,8,10];
    
    
              document.getElementById("p2").innerHTML=("We have seen in class that water spontaneously rises up when put in contact with a hydrophilic tube. A similar phenomenon occurs when water is put in contact with two parallel hydrophilic plates (see figure below). Given that the gap between the plates b = " + b[i] + " μm, the width of the plates L = " + L[i] + " cm, and the contact angle between the water and the plates is θ = " + theta[i] + " degrees, find the height of the capillary rise h.")
    
            </script>	
    
            <table class="image">
            <caption align="bottom">Two parallel hydrophilic plates.</caption>
            <tr><td><img src="https://i.ibb.co/CBsh4g5/fig2.png" class="center40" width=40%></td></tr>
            </table><hr></div>
    </li>
    <li>
        <div class="question"><p id="p3"></p>

            <script>
                
                var A1=[0.4,0.8,1.2,1.6,2];
                var A2=[10,20,30,40,50];
                var alpha=[10,20,30,40,50];
                var Q=[2,4,6,8,10];
                var V2=[2,4,5,10,15];
        
              document.getElementById("p3").innerHTML=("Water flows through a pipe fitting that splits the total flow into three parts (see figure below). The straight portions of the pipe have the same cross-sectional area A<sub>1</sub> = A<sub>2</sub> = " + A1[i] + " m<sup>2</sup>, while the angled pipes share the cross-sectional area A<sub>3</sub> = A<sub>4</sub> = " + A2[i] + " m<sup>2</sup>. The angle between the straight pipes and the stright pipe is α = " + alpha[i] + " degrees. <br><br> <br> Given the inlet flow rate Q<sub>1</sub> = " + Q[i] + " m<sup>3</sup>/s, the exit velocity of the straight pipe V<sub>2</sub> = " + V2[i] + " m/s, find the exit velocity in the angled pipes. <br> <br> The pipe fitting is anchored to the floor (gray) with a single screw (red). Assume viscous forces are negligible, determine the x and y components of the force that the pipe fitting exerts on the screw. Is this assumption valid?")
        
            </script>	
            
            <table class="image">
            <caption align="bottom">Pipe fitting that splits flow into three parts.</caption>
            <tr><td><img src="https://i.ibb.co/0fnq4WW/fig7.png"  class="center60" width=60%></td></tr>
            </table><hr>
        </div>
    </li>
    <li>
        <div class="question"><p id="p4"></p>
	
            <script>
                
                var Ft=[10,20,30,40,50];
        
              document.getElementById("p4").innerHTML=("Hurricanes can cause devastating damages to civil infrastructures due to high winds. For example, the maximum wind speed during Hurricane Matthew was recorded as 165 mph (miles per hour), which was powerful enough to rip the roof of some houses (see left figure below). Suppose that you decide to use a reinforced steel slab (10 m x 10 m) as the roof of your vacation home in Florida, which will be attached to the walls of the house by 200 bolts (see right figure below). <br><br> <br> Given that each bolt can sustain a maximum tensile force of " + Ft[i] + " N, apply Bernoulli's equation to determine whether the bolts will be able to withstand a hurricane as strong as Hurricane Matthew. You can assume that the air flow over the roof reaches the maximum wind speed recorded during Hurrican Matthew, and that the air inside the house is still. Please clearly illustrate your free-body diagram. <br> <br> What conservation laws is Bernoulli's equation based on? Write down at least 3 assumptions associated with Bernoulli's equation. Are these assumptions justified for this problem?")
        
            </script>
        
            <table class="image">
            <caption align="bottom">(a) Hurricane Matthew ripping roof off of home. (b)Reinforced steel slab.</caption>
            <tr><td><img src="https://i.ibb.co/hfhs7WG/fig2.png"  class="center" width=125%></td></tr>
            </table><hr>
        </div>
    </li>
    <li>
        <div class="question"><p id="p5"></p>
	
            <script>
                
                var dz=[10,20,30,40,50];
                var alpha=[10,15,20,25,30];
                var h=[1,2,3,4,5];
        
              document.getElementById("p5").innerHTML=("The bed of a concrete-lined clean and straight channel, with Manning's coefficient n = 0.03 s/m<sup>1/3</sup> drops " + dz[i] + " m every 1500 m. The stream has a trapezoidal cross section with an angle of inclination α = " + alpha[i] + " degrees. <br><br> <br> Given that the stream has a water depth of h = " + h[i] + " m (see figure (a) below), find the flow rate in the stream. <br> <br> A concrete divider with the same Manning's coefficient was installed at the middle of the stream (see figure (b) below). Given that the total flow rate in the stream stays the same, would the water depth in the stream change as a result of the divider? If so, would it increase or decrease? Would the stream velocity change? If so, would it increase or decrease? You may assume the thickness of the divider to be negligible.")
        
            </script>
        
            <table class="image">
            <caption align="bottom">(a) Original channel cross section. (b) Cross section of channel with divider installed.</caption>
            <tr><td><img src="https://i.ibb.co/njH0KTG/fig8.png"  class="center" width=125%></td></tr>
            </table><hr>
        </div>
    </li>
    <li>
        <div class="question"><p id="p6"></p>
	
            <script>
                
                var b=[10,20,30,40,50];
                var h1=[2,4,6,4,3];
                var hweir=[2,4,1,9,7];
        
              document.getElementById("p6").innerHTML=("Water is flowing in a channel with a rectangular cross-section. The channel has a uniform width of " + b[i] + " m, and it is equipped with a broad-crested weir. The height of flow in a channel far upstream of the weir is h<sub>1</sub> = " + h1[i] + " m, while the weir is h<sub>weir</sub> =" + hweir[i] + " m above the bed of the channel. <br><br> <br> Assuming the flow over the weir is critical, calculate the flow rate in the channel by iteratively solving for the critical depth h<sub>c</sub>. Perform at least 3 iterations. Did the flow rate converge? <br> <br> Given the water depth immediately downstream of the weir is 90% of the critical depth h<sub>c</sub>, what is the water depth after the flow experiences a hydraulic jump further downstream? <br> <br> How much energy is dissipated by the hydraulic jump?")
        
            </script>
        
            </table><hr>
        </div>
    </li>
    <li>
        <div class="question"><p id="p7"></p><script>
			
            var D=[2,4,6,4,3];
            var u=[2,4,1,9,7];
            var L=[10,20,30,40,50];
    
             document.getElementById("p7").innerHTML=("Olive oil is being pushed out of a tank through a tube (see figure below). <br><br> <br> Given that the relevant parameters of the problem are the tube diameter D= " + D[i] + " mm, the olive oil’s density and viscosity, and the exit velocity u = " + u[i] + " mm/s), derive the relevant dimensionless parameter for this problem using dimensional analysis and the Buckingham Pi theorem. What is the value of this parameter? <i>Note you can find the physical properties of olive oil in the equation sheet.</i> <br> <br> Assuming the pressure outside of the tube is atmospheric, the length of the tube L = " + L[i] + " cm, what is the internal pressure P<sub>in</sub> needed to sustain this flow?")
    
            </script>	
    
            <table class="image">
            <caption align="bottom"> Tank that olive oil is being pushed out of.</caption>
            <tr><td><img src="https://i.ibb.co/zn2q207/fig5.png"  class="center" width=100%></td></tr>
            </table><hr>
        </div>
    </li>
</ol>
</body>

<script>
    var ol = document.querySelector('ol');
    for (var i = ol.children.length; i >= 0; i--) {
        ol.appendChild(ol.children[Math.random() * i | 0]);
    }
</script>

</html>
