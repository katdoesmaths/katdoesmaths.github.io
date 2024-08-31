---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


Research Interests
----

My research lies in the boundary between theoretical and computational fluid dynamics. My PhD research used numerical methods to validate the theoretical assumptions around the presence of a lubricating air layer that is present beneath bouncing droplets. It was motivated by work done on hydrodynamic pilot-wave theory, and considered millimetric droplets rebounding on a liquid bath, at speeds where surface tension of the free surfaces is important.

During my PhD I was fortunate to be supervised by  [Prof. Paul Milewski](https://science.psu.edu/math/people/ppm5454), and collaborate with [Dr Radu Cimpeanu](https://www.raducimpeanu.com/). 

Post-PhD my research has had a large industrial motivation, as I completed a Knowledge Transfer Partnership with the University of Bath and Wessex Water, studying hydrodynamical models of river networks looking towards contaminant tracing. 

I am now part of the Centre for Applications of Mathematical and Computing Sciences at the University of Warwick, where I work on a series of impact driven research projects. 

****

Education
----

* PhD: "Filling the Gap on Droplet Dynamics", _University of Bath, 2024_
* MRes: "Elucidating the lubrication layer arising from impacting droplets", _University of Bath, 2020_
* MMath: "Proper generalized decomposition for partial differential equations", _University of Cardiff, 2019_

**** 

Publications
====


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
