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
I am an Assistant Professor with the Department of Artificial Intelligence at Catholic University of Korea, Bucheon, Korea. I was a Postdoctoral Fellow with the School of Electrical Engineering, Korea University, Seoul, Korea in 2023. I received the B.S. and Ph.D. degrees from Korea University, Seoul, Korea, in 2017 and 2023, respectively.

<br>

Latest News
======
{% for post in site.talks reversed %}
  {% include archive-single-news.html %}
{% endfor %}
