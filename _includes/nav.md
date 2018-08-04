[Home](https://2e0pgs.github.io/) {% for page in site.pages %}{% if page.nav == true %}| [{{ page.title }}]({{ page.url | absolute_url }}){% endif %}{% endfor %}
