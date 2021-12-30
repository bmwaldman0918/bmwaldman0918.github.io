---
layout: page
title: Projects
permalink: /projects/
order: 1
---
{% assign sorted_projects = site.projects | sort:"order" %}
<dl>
{% for p in sorted_projects %}
  <dt><a href="{{ p.url }}"><b>{{ p.title }}</b></a></dt>
  <dd>{{ p.summary }}</dd>
{% endfor %}
</dl>