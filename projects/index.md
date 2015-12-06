---
layout: page
title: Projects
comments: false
modified: 2015-12-06
---

<ul>
{% assign repos = site.github.public_repositories %}
{% for repo in repos %}
	<a href="{{ repository.html_url }}">
	<li>
	<div>{{ repository.name }}</div>
	<div>{{ repository.description }}</div>
	</li>
	</a>
{% endfor %}
</ul>
