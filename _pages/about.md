---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
======
I am a Master-Ph.D. joint course student in the School of Electrical Engineering at Korea University. I received the B.S. degree in the School of Electrical Engineering from Korea University in Feb 2017.

<br>
Latest News
======
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
