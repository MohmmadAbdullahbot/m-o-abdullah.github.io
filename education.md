---
layout: page
title: "Education"
permalink: /education/
---

{% for edu in site.data.education %}
### {{ edu.degree }}
**{{ edu.school }}**  
_{{ edu.date }}_
---
{% endfor %}
