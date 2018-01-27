---
title: Home
description: Homepage
---

{% include nav.md %}

![Banner](http://m3pgs.weebly.com/uploads/8/1/6/2/8162774/header_images/1411236150.jpg)

# Welcome to my website

### Contents:

{% for page in site.pages %}
{% if page.nav == true %}- [{{ page.title }}]({{ page.url | absolute_url }}){% endif %}
{% endfor %}
