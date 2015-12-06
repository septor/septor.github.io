---
layout: page
title: Projects
comments: false
modified: 2015-12-06
---

<ul>
{% for repository in site.github.public_repositories | sort: 'pushed_at' %}
	<a href="{{ repository.html_url }}">
	<li>
	<div>{{ repository.name }}</div>
	<div>{{ repository.description }}</div>
	</li>
	</a>
{% endfor %}
</ul>
