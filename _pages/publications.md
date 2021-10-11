---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Click on the items below to learn more. You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=rbAjLQYAAAAJ).

{% include base_path %}

<ol reversed>
{% for post in site.publications reversed %}
  <li>
  {% include archive-single.html %}
  </li>
{% endfor %}
</ol>