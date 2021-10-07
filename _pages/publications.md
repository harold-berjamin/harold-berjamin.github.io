---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar != null or author.googlescholar != "" %}
  You can also find my articles on {{ author.googlescholar }}.
{% endif %}

{% include base_path %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
