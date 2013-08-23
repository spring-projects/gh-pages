{% for badge in page.badges %}
	<div class="project-sub-link"><a href="{{ badge.url }}"><img class="logo" src="{{ badge.image_url }}" alt="{{ badge.name }}" title="{{ badge.name }}" width="32" height="32"/></a></div>
{% endfor %}
