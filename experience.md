---
layout: page
title: "Experience"
permalink: /experience/
---

{% for item in site.data.experience %}
### {{ item.title }} – {{ item.company }}
**{{ item.location }}**  
*{{ item.date }}*
{% if item.details %}
- {{ item.details | newline_to_br }}
{% endif %}
---
{% endfor %}
