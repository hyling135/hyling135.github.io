---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Computer Science, ETH Zürich, 2024 &ndash; present
* M.S. in Computer Science, ETH Zürich, 2021 &ndash; 2024
* B.S. in Computer Science and Technology, Peking University, 2016 &ndash; 2021

<!--
Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
-->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!--
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
-->

Internships and Projects
======
<ul>
  <div class="list__item">
    <article class="archive__item">
      <li>
        <h3 class="archive__item-title archive__item-title--plain"><strong>Practical Work</strong>, ETH Zürich, 2023</h3>
        <p class="archive__item-location">Zürich, Switzerland</p>
        <div class="archive__item-content">
          <p>Supervisors: Dr. Thibault Dardinier, Dr. Gaurav Parthasarathy, Prof. Dr. Peter Müller</p>
          <ul>
            <li>Formally defined least fixed point predicate interpretation for Viper’s abstract semantics, and derived an equirecursive semantics from it.</li>
            <li>Proved combinability and semantic multiplication and syntactic multiplication equivalence properties on satisfiability of Viper’s equirecursive semantics.</li>
          </ul>
        </div>
      </li>
    </article>
  </div>
</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!--
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
