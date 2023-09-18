---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
Research Interest
======
My research interests focus on the following areas
* Area 1: the application of machine learning in the following areas: mobile computing, internet of things, wireless sensor networks, ubiquitous computing
* Area 2: indoor localisation, mobile robotics
* Area 3: cyber security on IoT and mobile devices

My full list of publications are available in my [Google Citation](https://scholar.google.co.uk/citations?user=sm0c2cgAAAAJ&hl=en)

Potential PhD students
======
* Please send your CV and your transcripts to my email. I will get back to you at my earliest convenience. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


