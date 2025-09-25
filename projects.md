---
title: Projects
permalink: /projects/
---

# Projects

<ul>
{% for project in site.projects %}
  <li>
    <a href="{{ project.url | relative_url }}">{{ project.title }}</a> — {{ project.date | date: "%b %d, %Y" }}
  </li>
{% endfor %}
</ul>
