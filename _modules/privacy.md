---
permalink: /modules/privacy/
layout: home
title: Privacy, Surveillance, and Free Speech
nav_order: 3
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
* [User Interviews](/modules/privacy/assignments/#assignment-1-user-interviews)
