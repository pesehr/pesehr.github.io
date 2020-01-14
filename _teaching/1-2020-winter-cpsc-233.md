---
title: "CPSC 233 - Introduction to Computer Science for Computer Science Majors II - Winter 2020
"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/CPSC233w20
venue: "University of Calgary, Computer Science Department, Winter"
date: 01-01-2020
location: "Calgary, Canada"
---

Continuation of Introduction to Computer Science for Computer Science Majors I. Emphasis on object-oriented analysis and design of small-scale computational systems and implementation using an object oriented language. Issues of design, modularization, and programming style will be emphasized.

<a href="https://pesehr.youcanbook.me">Book an appointment</a>


<details>
<summary>Slides</summary>
<br>
<ul>
{% assign materials = site.static_files | where: "course", CPSC233W20 %}
{% for material in materials %}
{% if material.path contains "CPSC233W20/slides"%}
  <li><a href="{{ material.path }}">{{material.name}}</a></li>
{% endif %}
{% endfor %}
</ul>
</details>

----
<details>
<summary>Exercises</summary>
<br>
<ul>
{% assign materials = site.static_files | where: "course", CPSC233W20 %}
{% for material in materials %}
{% if material.path contains "CPSC233W20/exercises"%}
  <li><a href="{{ material.path }}">{{material.name}}</a></li>
{% endif %}
{% endfor %}
</ul>
</details>
