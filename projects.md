---
layout: page
title: Projects
---

Repository Name | Forks | Stargazers
----------------|-------|-------------
{% for repository in site.github.public_repositories %}
	[{{ repository.name }}]({{ repository.html_url  }}) | {{ repository.forks_count }} | {{ repository.stargazers_count }}
{% endfor %}
