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
  <img src='/images/Logo_EU_V.png' width="143" height="143" alt="EU emblem">
  <img src='/images/Logo_MC.png' width="143" height="143" alt="MSCA logo">
</figure>

<address>
School of Mathematical and Statistical Sciences, NUI Galway<br>
University Road, Galway, H91 TK33, Republic of Ireland
</address>

News
======

{% for post in site.posts limit:5 reversed %}
  {% include archive-single.html %}
{% endfor %}