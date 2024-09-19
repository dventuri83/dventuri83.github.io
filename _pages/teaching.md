---
layout: page
permalink: /teaching/
title: teaching (draft)
description: This page contains all the courses I am currently teaching at the university.
nav: true
nav_order: 6
display_categories: teaching
horizontal: false
---

<!-- pages/projects.md -->
<div class="teaching">

<!-- Display projects without categories -->

{% assign sorted_projects = site.teaching | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
