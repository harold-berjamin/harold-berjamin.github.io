---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About
======

I joined [NUI Galway](http://www.nuigalway.ie/our-research/people/mathematics-statistics-and-applied-mathematics/haroldberjamin/) in 2019 to work as a Postdoctoral Research Fellow in Applied Mathematics with [Michel Destrade](http://www.maths.nuigalway.ie/~destrade/). My research concerns the propagation of mechanical waves in nonlinear materials (theoretical and numerical aspects). In particular, I study the nonlinear dynamic behavior of viscoelastic and poroelastic solids. This research has various applications in engineering, e.g. in geophysics, biomechanics, nondestructive testing and materials science.

My current [research project](https://cordis.europa.eu/project/id/101023950) concerns the subject of traumatic brain injury. It has received funding from the European Union’s Horizon 2020 research and innovation programme. You can contact me by email for opportunities, scientific discussions or communication requests.

<figure>
  <img src='/images/Logo_EU_V.png' alt="EU emblem" width="143" height="143" alt="EU Funding">
  <img src='/images/Logo_MC.png' alt="MSCA logo" width="143" height="143" alt="MSCA">
</figure>

<address>
School of Mathematical and Statistical Sciences, NUI Galway<br>
University Road, Galway, H91 TK33, Republic of Ireland<br>
</address><br>

News
======

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}