---
permalink: /modules/ethics/
layout: home
title: Ethics and Values
nav_order: 1
has_children: true
has_toc: false
---

{% assign modules = site.modules | where:"parent", page.title | sort: "nav_order" %}

# {{ page.title }}
{{ site.h2_available_submodules }}
{% for module in modules -%}
{% unless module.title == "Assignments" -%}
* {% include get_url.html title=module.title permalink=module.permalink %}
{%- endunless %}
{% endfor %}

{{ site.h2_available_assignments }}
* [Critical Analysis and Argumentation](/modules/ethics/assignments/#assignment-1-critical-analysis-and-argumentation)