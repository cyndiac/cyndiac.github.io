---
title: "Walk‐Burrow‐Tug: Legged anchoring analysis using RFT‐based granular limit surfaces"
collection: publications
permalink: /publication/walk-burrow-tug
excerpt: 'This work validates that the load capacity of sand can be represented by a limit surface generated via RFT. Knowledge of the load direction also allows one to estimate the resulting direction of displacement once media failure occurs.<br/><img src='/images/tug.png' width='60%'>'
date: 2023-04-21
venue: 'IEEE Robotics and Automation Letters'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10106433'
citation: 'T. M. Huh, C. Cao, J. Aderibigbe, D. Moon, and H. S. Stuart, “Walk-Burrow-Tug: Legged anchoring analysis using RFT-based granular limit surfaces,” IEEE Robot. Autom. Lett., Apr. 2023, doi: 10.1109/LRA.2023.3269324.'
---

<!-- Specify contribution to work. -->

We develop a new resistive force theory based granular limit surface (RFT-GLS) method to predict and guide behaviors of forceful ground robots. As a case study, we harness a small mobile robotic system - MiniRQuad (296g) - to ‘walk-burrow-tug;’ it actively exploits ground anchoring by burrowing its legs to tug loads. RFT-GLS informs the selection of efficient strategies to transport sleds with varying masses. The granular limit surface (GLS), a wrench boundary that separates stationary and kinetic behavior, is computed using 3D resistive force theory (RFT) for a given body and set of motion twists. This limit surface is then used to predict the quasi-static trajectory of the robot when it fails to withstand an external load. We find that the RFT-GLS enables accurate force and motion predictions in laboratory tests. For control applications, a pre-composed state space map of the twist-wrench pairs enables computationally efficient simulations to improve robotic anchoring strategies.

<center> 
<img src="/images/tug.png"  width="60%"> 
<img src="/images/limsurf_gen.png"  width="60%"> 
</center>