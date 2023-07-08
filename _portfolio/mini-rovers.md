---
title: "Mini Rovers"
excerpt: "I've built some fun small rovers while working on my graduate research... click here for some images."
collection: portfolio
---

~Work in progress...~

In support of my research, I've built some small scaled rovers to test different wheel controllers. They're nothing fancy but they're good enough to produce and measure the effects I'm interested in. They use some combination of Arduino / Teensy / Raspberry Pi to command motor controllers (steppers, RoboClaw -- brushed DC, ODrive -- brushless DC) and read in digital sensor outputs via SPI / CAN / serial / I2C.

For onboard telemetry, I've used onboard current sensors, IMU's, time of flight sensors (to measure wheel sinkage and rover linear velocity), and quadrature encoders. For motion capture, I used ArUco (April Tag) tracking, OptiTrack, and Vicon camera systems.

This simple rover drives the front and back wheels at different speeds in order to increase travel velocity under large resistance loads (be it a towed load or gravity on a slope), since the loading causes different sinkage levels of each pair of wheels in soft media. More information is available [here](https://cyndiac.github.io/publication/fb-diff-drive).

<!-- <center>  -->
	<img src="/images/diffslip_setup.jpg"> 
<!-- </center> -->

<!-- <br> -->

This rover now has "legs" that extend and contract its wheelbase to perform inch-worming gaits. From a baseline where all the wheels drive at the same, equal speed, I was able to achieve an 8x travel efficiency improvement on 20° slopes by inch-worming and operating the driving wheels in a more favorable slip regime. More information is available [here](https://cyndiac.github.io/publication/inchworm).

<center>
	<img src="/images/shifty.png"> 
</center>


As a side project, I also helped my labmate design a winch for his tethered robotics work. I used a levelwinder from a fishing reel to keep the cable neat, and the winch is built upon a load cell on a swiveling base in order to measure the direction and magnitude of the tethered load. These images & gifs are courtesy of Justin Page.

<center>
	<img src="/images/winch.png"> 
	<img src="/images/winch.gif"> 
	<img src="/images/winch_sand.gif"> 
</center>


I have also designed and built a larger rover (~24" square) that quickly shifts around its battery as ballast in order to redistribute its contact loads on the ground. My hypothesis is that oscilliatory loading may be more useful than balanced wheel loading in getting over obstacles and climbing sandy slopes, but I've run out of time in my PhD to test this! Pictures will be uploaded when I have a chance to get nice images, but for now here's a quick CAD. The suspension is fully passive but I use springs rather than a rocker or bogie to ensure that the shifted loads make their way to the wheels, rather than being equalized by kinematics.

<center>
	<img src="/images/babybot_cad.png"> 
</center>

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
