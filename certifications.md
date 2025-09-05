---
layout: page
title: "Certifications"
permalink: /certifications/
---

{% for cert in site.data.certifications %}
- **{{ cert.name }}** – {{ cert.authority }}  
  {% if cert.issued %}Issued: {{ cert.issued }}{% endif %}{% if cert.expires %} | Expires: {{ cert.expires }}{% endif %}
{% endfor %}
