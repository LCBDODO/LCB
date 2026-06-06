---
layout: page
title: projects
permalink: /projects/
description: Major research projects in the Lab of Cancer Biology.
nav: true
nav_order: 3
display_categories: [research, approaches]
horizontal: false
---

# Projects

Our projects focus on therapy resistance, cancer cell vulnerability, immune evasion, metabolism, and translational biomarker discovery.

{% if site.enable_project_categories and page.display_categories %}
  {% for category in page.display_categories %}
    <h2>{{ category | capitalize }}</h2>
    {% assign categorized_projects = site.projects | where: "category", category %}
    {% assign sorted_projects = categorized_projects | sort: "importance" %}
    <div class="projects">
      {% for project in sorted_projects %}
        {% include projects.liquid %}
      {% endfor %}
    </div>
  {% endfor %}
{% else %}
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="projects">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
{% endif %}
