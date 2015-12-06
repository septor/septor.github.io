---
layout: page
title: Projects
comments: false
modified: 2015-12-06
---

<ul>
{% assign repos = site.github.public_repositories | sort: 'pushed_at' %}
{% for repo in repos %}
	<a href="{{ repo.html_url }}">
	<li>
	<div>{{ repo.name }}</div>
	<div>{{ repo.description }}</div>
	</li>
	</a>
{% endfor %}
</ul>
