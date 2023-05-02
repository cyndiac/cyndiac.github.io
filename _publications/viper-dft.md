---
title: "Actuated Suspension Tuning Characterization of the VIPER Lunar Rover"
collection: publications
permalink: /publication/viper-dft
excerpt: "VIPER will be the first rover with an active suspension to launch on a NASA mission. This work experimentally characterizes the mobility performance of VIPER's load-responsive suspension controller as it traverses typical terrains with different tuning parameters."
date: 2023-03-10
venue: 'IEEE Aerospace Conference'
paperurl: 
# paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10106433'
citation: 'C. Cao, A. Rogg, A. Tardy, “Actuated Suspension Tuning Characterization of the VIPER Lunar Rover,” in 2023 IEEE Aerospace Conference, Mar. 2023.'
---

<!-- Insert video of VIPER rock on slope. Or the stance image -->


NASA’s Volatiles Investigating Polar Exploration Rover (VIPER) possesses a unique suspension configuration that has not yet flown in previous missions. Its mobility system must go through rigorous evaluation to build confidence in its performance. VIPER’s actuated suspension is commanded by an attitude tracking controller followed by a down-force thresholder (DFT) to maintain wheel-to-ground contact. This paper provides an overview of the initial characterization of the sensitivity of the rover’s terrain traversability to its wheel normal load threshold tuning. The long-term objective is to understand how suspension tuning will impact the mobility of the flight vehicle during the mission in the lunar environment. The rover traversed a series of nominal case and bounding case roving scenarios while the tuning parameters were varied, and its mobility was evaluated with respect to slip, power, and stability.

The data confirm that the DFT increases wheel-to-ground contact and balances load between wheels, and the improvements scale with high load thresholds and suspension response speeds. However, load cell noise and low control-loop-frequency can cause the suspension to oscillate, especially when combined with poorly tuned parameters and with high suspension response speeds. In the experiments, the DFT maintained or improved mobility relative to using only the attitude tracker, but variation in the DFT tuning did not significantly impact slip or power consumption. Chassis stability was the most sensitive metric to tuning; fast and responsive tuning reduced body rotation rates while traversing large rocks but caused suspension oscillation in nominal maneuvers on slopes. Hence, DFT activation should be concentrated on large obstacles rather than nominal maneuvers. Low load thresholds combined with a moderate suspension speed provide a good balance between vehicle stability in rough terrain and internal control stability.

This tuning allows motor actuation requirements, power consumption, and controller instability risk to be reduced without impacting traversability requirements. Future testing in higher- fidelity lunar simulant can expand on these results, since softer regolith may provide more challenge to the rover’s traction performance and produce stronger dependencies between slip and load distribution. Thus far, this testing has narrowed tuning parameters down to a robust window and reduced mission risk by characterizing mobility behavior across a wide spectrum of potential parameters.




