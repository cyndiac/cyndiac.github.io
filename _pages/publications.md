---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Planetary rovers have a history of entrapment in soft Martian sand, which is difficult to visually anticipate and results in high-stakes extrication efforts. NASA will soon return to the moon to scout for water ice and other resources in polar craters, which may be composed of sloped loose regolith. As scientific objectives on Mars evolve and interest in lunar exploration increases, the need to traverse loose, sandy terrain incentivizes the design of more energy-efficient locomotion suspensions and gaits. 
To tackle this challenge, I investigated the effects of weight distribution and induced wheel slip on mobility using miniature rovers in the lab and the Volatiles Investigating Polar Exploration Rover (VIPER) mobility representative rover at NASA. 

*Key words*: planetary rover, field robotics, sandy slopes, granular resistive force theory, wheel-terrain interaction


<center> 
<img src="/images/shifty.png"  width="40%">
<img src="/images/mgru.jpg"  width="55%"> 
</center>


Click on the paper titles for more information and images.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
