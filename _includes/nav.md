{% for page in site.pages %}
	{% if page.nav == true %}
		| [{{ page.title }}]({{ page.url | absolute_url }})
	{% endif %}
{% endfor %}
