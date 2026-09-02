---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
published: false   # not part of the site for now; see /internships-and-projects/
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

{% comment %}
Internships and Projects
======
The entries now live in _pages/internships-and-projects.html, which is their
only copy. If this CV page is ever re-enabled, either move them back here or
pull them in from that page with:
  {% raw %}{% assign ip = site.pages | where: "path", "_pages/internships-and-projects.html" | first %}{{ ip.content }}{% endraw %}
{% endcomment %}

Teaching
======
{% comment %}
The template's original approach listed the _teaching collection here:
  {% raw %}<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>{% endraw %}
Those demo items are disabled (`published: false` under the _teaching defaults
in _config.yml) and the entries are hand-written below, mirroring
_pages/teaching.html, which is their other copy.
{% endcomment %}
* Teaching Assistant, ETH Zürich, Zürich, Switzerland
  * Applied Cryptography (2023)
  * Concepts of Object-Oriented Programming (2024)
  * Research Topics in Software Engineering (2024)
  * Computer Science I &ndash; D-ITET (2025 and 2026)
  * Theoretical Computer Science (2025)
  * Computer Science II &ndash; D-ITET (2026)

* Teaching Assistant, Peking University, Beijing, China
  * Introduction to Computer Systems (2019 and 2020)
  * Foundamentals of Cryptography (2020)

<!--
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
