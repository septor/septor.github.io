---
layout: page
title: Projects
comments: false
modified: 2015-12-06
---

<ul>
{% assign repos = site.github.public_repositories | sort: 'pushed_at' %}
{% for repo in repos %}
	<li>
	<div><a href="{{ repository.html_url }}">{{ repository.name }}</a></div>
	<div>{{ repository.description }}</div>
	</li>
{% endfor %}
</ul>
