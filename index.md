---
title: Home
description: Homepage
---

{% include social.md %}

{% include nav.md %}

{% include banner.md %}

# Welcome to my website

### Contents:

{% for page in site.pages %}
{% if page.nav == true %}- [{{ page.title }}]({{ page.url | absolute_url }}){% endif %}
{% endfor %}
