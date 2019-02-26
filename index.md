---
layout: home
image:
  path: "/assets/img/splash.jpg"
  caption: "Photo by [Sebastian Unrau](https://unsplash.com/photos/sp-p7uuT0tw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com)"
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
