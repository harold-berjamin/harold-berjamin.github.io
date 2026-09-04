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

My research concerns the mathematics and mechanics of complex materials. My works are dedicated to the modelling of geomaterials, soft biological tissues, composite materials, active metamaterials, and thin structures. Focus is on the modelling of wave propagation, the study of bifurcations, as well as the development of related computational methods. The results have various applications in engineering, e.g. in geophysics, biomechanics, nondestructive testing and materials science.

Previously, I was a postdoctoral researcher working with [Doireann O'Kiely](https://www.doireannokiely.com/) at the University of Limerick (Ireland), with [Stephan Rudykh](https://scholar.google.com/citations?user=gGiZAKUAAAAJ) at the University of Galway (Ireland), and with [Michel Destrade](https://maths.nuigalway.ie/~destrade/about.shtml) at the same institution. In particular, I led a [research project](https://cordis.europa.eu/project/id/101023950) on traumatic brain injury, and I have contributed to a [project](https://cordis.europa.eu/project/id/852281) on soft magnetoactive materials.

You can contact me by email for opportunities, scientific discussions or communication requests.

<address>
School of Engineering, University of Galway,<br>
Galway, H91 TK33, Ireland​
</address><br>

News
======

{% for post in site.posts limit:5 reversed %}
  {% include archive-single.html %}
{% endfor %}