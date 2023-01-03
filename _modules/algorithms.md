---
permalink: /modules/algorithms/
layout: home
title: Algorithmic Decision-Making
nav_order: 4
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