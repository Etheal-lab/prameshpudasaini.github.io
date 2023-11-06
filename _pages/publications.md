---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Last updated: November 5, 2023

# Journal Papers

{% for entry in site.data.citations %}
  {% if entry.category == "journal" %}
    - **{{ entry.title }}**  
    {{ entry.author }}  
    *{{ entry.journal }}*, {{ entry.year }}.
  {% endif %}
{% endfor %}

# Technical Reports

{% for entry in site.data.citations %}
  {% if entry.category == "report" %}
    - **{{ entry.title }}**  
    {{ entry.author }}  
    *{{ entry.journal }}*, {{ entry.year }}.
  {% endif %}
{% endfor %}

# Thesis

{% for entry in site.data.citations %}
  {% if entry.category == "thesis" %}
    - **{{ entry.title }}**  
    {{ entry.author }}  
    *{{ entry.journal }}*, {{ entry.year }}.
  {% endif %}
{% endfor %}

# Conference Presentations

{% for entry in site.data.citations %}
  {% if entry.category == "conference" %}
    - **{{ entry.title }}**  
    {{ entry.author }}  
    *{{ entry.journal }}*, {{ entry.year }}.
  {% endif %}
{% endfor %}

# Invited Talks & Presentations

{% for entry in site.data.citations %}
  {% if entry.category == "presentation" %}
    - **{{ entry.title }}**  
    {{ entry.author }}  
    *{{ entry.journal }}*, {{ entry.year }}.
  {% endif %}
{% endfor %}