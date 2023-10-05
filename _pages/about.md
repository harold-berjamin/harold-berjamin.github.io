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

My research concerns the propagation of mechanical waves in nonlinear materials (theoretical and numerical aspects). In particular, I study the nonlinear dynamic behavior of viscoelastic and poroelastic solids. This research has various applications in engineering, e.g. in geophysics, biomechanics, nondestructive testing and materials science.

Currently I am a postdoctoral researcher working with [Stephan Rudykh](https://scholar.google.com/citations?user=gGiZAKUAAAAJ) at the [University of Galway](https://www.universityofgalway.ie/science-engineering/school-of-maths/staff-profiles/academic/haroldberjamin/) (Ireland), as part of the [ERC project MAGIC](https://cordis.europa.eu/project/id/852281). This research addresses the modelling of soft magnetoactive materials.

I joined the University of Galway in 2019 to work as a postdoctoral fellow in Applied Mathematics with [Michel Destrade](https://www.universityofgalway.ie/science-engineering/school-of-maths/staff-profiles/academic/micheldestrade/). This [research project](https://cordis.europa.eu/project/id/101023950) concerned the subject of traumatic brain injury. It has received funding from the European Union's Horizon 2020 research and innovation programme.

You can contact me by email for opportunities, scientific discussions or communication requests. <em> Looking for job opportunities (Assistant Professor, Lecturer, Researcher, Scientist). </em>

<figure>
  <img src='/images/Logo_EU_V.png' width="143" height="143" alt="EU emblem">
</figure>

<address>
School of Mathematical and Statistical Sciences, University of Galway<br>
University Road, Galway, H91 TK33, Republic of Ireland
</address><br>

News
======

{% for post in site.posts limit:5 reversed %}
  {% include archive-single.html %}
{% endfor %}