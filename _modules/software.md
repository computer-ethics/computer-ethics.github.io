---
permalink: /modules/software/
layout: home
title: Software Risks and Case Studies
nav_order: 2
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