---
title: "Granular Resistive Force Theory Implementation for Three-Dimensional Trajectories"
collection: publications
permalink: /publication/rft-3d
excerpt: "RFT is an empirical model of the forces on a body as it moves through sand. Its output is purely dependent on body geometry and velocity. This work extends the original 2D model to 3D using one additional internal model parameter and no additional media-specific parameters.<br><img src='/images/rft3d_ellipsoid.png'>"
date: 2021-02-03
venue: 'IEEE Robotics and Automation Letters'
paperurl: 'https://ieeexplore.ieee.org/document/9345981'
citation: 'L. K. Treers, C. Cao, and H. S. Stuart, “Granular Resistive Force Theory Implementation for Three-Dimensional Trajectories,” IEEE Robot. Autom. Lett., vol. 6, no. 2, pp. 1887–1894, Apr. 2021, doi: 10.1109/LRA.2021.3057052.'
---

<!-- Specify contribution to work. -->
<!-- Include gif of oscillation w/ forces; from main.m; also link github page here -->

Modelling interaction forces as bodies intrude into granular media is a longstanding challenge in the design and control of machines that navigate and manipulate these highly complex materials. Granular Resistive Force Theory, or RFT, is a flexible, reduced-order model for predicting intrusion forces on bodies in granular media. 2D RFT describes the forces on a plate whose velocity and normal vectors lie in the same vertical plane. We introduce a 3D RFT method that projects the total velocity vector into two scenarios that can already be described by 2D RFT, which allows us to extend the model into 3D with minimal additional experimental characterization. We then superimpose these independently calculated forces, weighted by experimentally fit scaling factors, to determine the total force on the plate. When applied to discretized convex hulls, this method performs force estimates of arbitrary trajectories in 3D space. The proposed formulation predicts forces experienced by oscillating and circumnutating bodies, motions motivated by mole crab burrowing and plant root growth respectively. This method is well-suited to complement more complex computational tools, such as Discrete Element Method. By expanding the application of RFT to 3D scenarios, a broader set of real-world applications can now be analyzed.

Github code: [https://github.com/embodied-dexterity-group/granular_rft_3D](https://github.com/embodied-dexterity-group/granular_rft_3D)

<center>
	<img src='/images/rft3d.gif' width='50%'>
</center>