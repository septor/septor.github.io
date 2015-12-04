---
layout: page
title: Projects
---

{% for repository in site.github.public_repositories %}
	* [ {{ repository.name }} ]({{ repository.url  }}) - {{ repository.language }}
{% endfor %}
