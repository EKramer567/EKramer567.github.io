<html>
    <style>
.centerAlignObject{
        text-align: center;
        }
a.button {
    background-color: #64B70E; /* Green */
    border: none;
    color: white;
    padding: 15px 120px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
}
        
img.autoscale{
    height: auto;
    width: auto;
}
     </style>
</html>
<div style="background-color:#444444; padding:10px;">
<p align="center">
    Greetings, and welcome to my site!<br>
    This site was created with Github Pages and Jekyll.<br>
    You can see the repository for this site by clicking the "View on GitHub" button above!
    <br><br>
    Below is a compilation of projects I have completed and some I am currently working on.
    I'm planning to put a lot of other small projects up here in the next few weeks.
    <br><br>
    Contact info:<br>
    ekramer567@gmail.com<br>
    LinkedIn: <a href="https://www.linkedin.com/in/ekramer567">www.linkedin.com/in/ekramer567</a>
    </p>
</div>

---

<div class ="centerAlignObject">
    <h1>Quadcopter Simulator</h1>
    <img src="QuadcopterSimPic.png"><br>
<a href="/assets/unity/Quadcoptersim/index.html" class="button">Play</a>
</div>

<div style="background-color:#444444; padding:10px;"> 
<p align="center">
    This is my attempt at a quadcopter simulator, using a USB/Bluetooth controller. I made this with Unity using C#, and no plugins or asset store assets. Making this playable in a browser window required building it in WebGL form and pushing the build to the repository for this site. You can find this project on my github here: 
    <a href="https://github.com/EKramer567/Quadcopter-Simulator">Quadcopter Simulator Repository</a><br><br>
                                                   
Before I move on to my next project, I want to fix one bug that I've been trying to fix for a while: if the copter's Yaw goes near 180 degrees relative to its starting rotation, <i>the PID balancing makes the copter flip back toward zero degrees</i>. If you have an idea what's causing that, I'm open to suggestions.<br>
I think I will also mess around with the terrain tool and maybe get some free environment object assets to put in there just to make it look better. Eventually I want to figure out how to allow the use of WebVR, but that might be another project.
</p>
</div>
  
---
---

<div class ="centerAlignObject">
    <h1>Hero Landing!</h1>
    <img src="HLscreenshot.png" width="300" height="475"><br>
<a href="https://play.google.com/store/apps/details?id=com.EKramer.HeroEntranceTraining" class="button">Go to Google Play Page</a>
</div>
<div style="background-color:#444444; padding:10px;"> 
<p align="center">
<i>Hero Landing!</i> is a small mobile game that I completed and published to the Google Play Store myself. I made this with Unity using C#. I used plugins for ads and microtransactions, and SFX/Music from the asset store. I chose to keep its repository private, since it is a monetized published game. If you'd like to see some snippets of the code that went in to <i>Hero Landing!</i>, please email me and I can get those for you.
</p>
</div>
  
---
---
