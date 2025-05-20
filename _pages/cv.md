---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Employment
======
* 2019-2025: Postdoctoral researcher, University of Galway, Ireland
* 2018-2019: Teaching and Research Assistant, Centrale Méditerranée, France
* 2015-2018: Doctoral fellow ([thesis](https://theses.hal.science/tel-01977206)), Aix-Marseille University, France

Education
======
* PhD in Acoustics, Aix-Marseille University, France, 2018
* MSc in Acoustics, Centrale Méditerranée, France, 2015
* MSc in Engineering, Centrale Méditerranée, France, 2015

Teaching
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Service
======
* Peer-review for [various journals](https://www.webofscience.com/wos/author/rid/B-1073-2017)
* 2025: Guest Editor for a [special issue](https://www.sciencedirect.com/special-issue/322343/the-rajagopal-legacy-innovations-in-continuum-mechanics-and-beyond) of Applications in Engineering Science
* 2022: Contribution to outreach during Maths Week Ireland ([I'm a Mathematician](https://imamathematician.ie/), [Bright Club Ireland](https://youtu.be/UdR5hvhJIRo))
* 2020-*: Member of the Research and Graduate Studies committee, University of Galway
* 2020-2021: Participation in a successful [Athena SWAN](https://www.advance-he.ac.uk/equality-charters/international-charters/athena-swan-ireland) bronze award application, University of Galway
* 2016-2017: PhD student representative, Institute of Mechanics and Acoustics, Marseille

Awards
======
* 2019: Thomas Mitchell Medal of Excellence, Irish Research Council
* 2019: PhD thesis prize, Doctoral School 353, Aix-Marseille University
* 2017: 3rd poster prize, ICNEM ’17 conference

Funding
======
* 2021: Marie Skłodowska-Curie Individual Fellowship ([project](https://cordis.europa.eu/project/id/101023950)), European Commission - Principal Investigator
* 2020: Ulysses grant, Irish Research Council - Participant
* 2019: Government of Ireland Postdoctoral Fellowship, Irish Research Council - Principal Investigator
* 2016: SLOWDYN, Défi Inphyniti, French centre for scientific research (CNRS) - Participant
* 2015: Doctoral Fellowship, French ministry of higher education and research - Principal Investigator

Selected publications
======
Go to [full list](https://harold-berjamin.github.io/publications/).
<ul>
  {% for post in site.publications reversed %}
    {% if post.cv %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>
