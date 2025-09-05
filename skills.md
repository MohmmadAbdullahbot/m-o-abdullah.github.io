---
layout: page
title: "Skills"
permalink: /skills/
---

<ul>
{% for skill in site.data.skills %}
<li>{{ skill }}</li>
{% endfor %}
</ul>
