{% if page.badges.twitter %}
<div class="project-sub-link"><a href="https://twitter.com/{{ page.badges.twitter }}"><img class="logo" src="http://www.health2con.com/events/files/twitter-logo-square-150x150.png" alt="Twitter" title="Twitter" width="32" height="32"/></a></div>
{% endif %}

{% for badge in page.badges.custom %}
<div class="project-sub-link"><a href="{{ badge.url }}"><img class="logo" src="{{ badge.image_url }}" alt="{{ badge.name }}" title="{{ badge.name }}" width="32" height="32"/></a></div>
{% endfor %}
