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
* 2019-2023: Postdoctoral fellow, NUI Galway, Ireland
* 2018-2019: Teaching and Research Assistant, Ecole Centrale de Marseille, France
* 2015-2018: Doctoral fellow ([thesis](https://tel.archives-ouvertes.fr/tel-01977206)), Aix-Marseille University, France

Education
======
* PhD in Acoustics, Aix-Marseille University, France, 2018
* MSc in Acoustics, Ecole Centrale de Marseille, France, 2015
* MSc in Engineering, Ecole Centrale de Marseille, France, 2015

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service
======
* Peer-review for [various journals](https://publons.com/researcher/2163976/harold-berjamin/peer-review/)
* 2020-*: Member of the Research and Graduate Studies committee, NUI Galway
* 2020-2021: Participation in a successful Athena SWAN bronze award application, which aim is to promote good practice in terms of gender equality in higher-education and research institutions, NUI Galway
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
