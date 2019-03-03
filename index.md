---
layout: home
image:
  path: "/assets/img/splash.jpg"
title: Gingerbeard
---

<center><p><em>Some musings on schizophrenia</em></p></center>

# Facts
<ul>
{% for fact in site.facts %}
  <li><h2><a href="{{ fact.url }}">{{ fact.title }}</a></h2></li>
{% endfor %}
</ul>

# Posts
