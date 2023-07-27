---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<!-- This page is still a work in progress... :) -->

<!-- If I had to summarize my key skills in a few words, I would pick: **mechanism design, rapid prototyping, and microcontroller integration.** -->
Key skills: **mechanism design, rapid prototyping, microcontroller integration**

My undergraduate focus was on machine design and classical control. 
Then I took a gap year and worked at SpaceX and Apple, both of which gave me context in industry & manufacturing.
In graduate school, I use my mechatronics knowledge as a tool for innovating in smarter, more efficient interaction with terrain. The skills I developed more recently are systems level: characterizing performance, designing experiments, and motivating work with first order principles.

<!-- TODO: Make notes about skills! Both past & present -->

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

