<p align="center">
    Greetings, and welcome to my site!
    I'm currently doing some experiments with putting games made in Unity (and exported in WebGL form) in to web pages you can access here
    Check back later and see what I have to show you!
    </p>

<html>
    <style>
.centerAlignObject{
        text-align: center;
        }
a.button {
    background-color: #64B70E; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
}
     </style>
   
<div class ="centerAlignObject">
    <h1>Quadcopter Simulator</h1>
    <img src="QuadcopterSimPic.png">
              <p> </p>
<a href="/assets/unity/Quadcoptersim/index.html" class="button">Play</a>
</div>
<p align="center">
    This is my attempt at a quadcopter simulator, using a USB/Bluetooth controller. At the moment, you can only control the copter with the USB controller, but for the moment I just want to get this up here. You can find the project on my github here: 
    <a href="https://github.com/EKramer567/Quadcopter-Simulator">LINK</a>
</p>
<p align="center">                                                      
Before I move on to my next project, I'm going to add keyboard controls for the sake of this site, and I want to fix one bug that I've been trying to fix forever: if the copter's Yaw goes near 180 degrees relative to its starting rotation, the PID balancing makes the copter flip out unexpectedly. I might also mess around with the terrain tool and maybe get some free tree assets to put in there just to make it look a bit better. Eventually I want to figure out how to allow the use of WebVR on these pages.
</p>
</html>
