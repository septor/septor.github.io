---
layout: page
title: Projects
comments: false
modified: 2015-12-06
---

<ul>
{% for repository in site.github.public_repositories %}
	<li>
	<div><a href="{{ repository.html_url }}">{{ repository.name }}</a></div>
	<div>{{ repository.description }}</div>
	</li>
{% endfor %}
</ul>
