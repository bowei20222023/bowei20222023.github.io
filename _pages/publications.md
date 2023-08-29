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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Research Interest
======
My research interests focus on the following areas
* Area 1: the application of machine learning in the following areas: mobile computing, internet of things, wireless sensor networks, ubiquitous computing
* Area 2: indoor localisation, mobile robotics
* Area 3: cyber security on IoT and mobile devices

Potential PhD students
======
* Please send your CV and your transcripts to my email. I will get back to you at my earliest convenience. 
