---
layout: page
title: Projects
---

{% for repository in site.github.public_repositories %}
	* [{{ repository.name }}]({{ repository.repository_url  }}) - {{ repository.language }}
{% endfor %}
