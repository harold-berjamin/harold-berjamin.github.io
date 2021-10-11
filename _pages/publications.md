---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Click on the items below to learn more. You can also find my articles on <a href="https://scholar.google.com/citations?user=rbAjLQYAAAAJ">my Google Scholar profile</a>.

{% include base_path %}

<ol reversed>
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
</ol>
