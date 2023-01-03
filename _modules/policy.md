---
permalink: /modules/policy/
layout: home
title: Technology Law and Policy
nav_order: 5
has_children: true
has_toc: false
---

{% assign modules = site.modules | where:"parent", page.title | sort: "nav_order" %}

# {{ page.title }}
{{ site.h2_available_submodules }}
{% for module in modules -%}
* {% include get_url.html title=module.title permalink=module.permalink %}
{% endfor %}