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

Key words: planetary rover, sandy slopes, granular resistive force theory, field robotics, mobility metrics, wheel-terrain interaction

Click on the paper titles for more information and images.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
