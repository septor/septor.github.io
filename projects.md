---
layout: page
title: Projects
---
<ul>
{% for repository in site.github.public_repositories %}
	<li><a href="{{ repository.html_url }}">{{ repository.name }}</a></li>
{% endfor %}
</ul>
