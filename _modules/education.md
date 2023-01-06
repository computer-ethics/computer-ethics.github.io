---
permalink: /modules/ethics/education/
layout: home
title: Teaching Ethics
parent: Ethics and Values
nav_order: 2
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>

1. What do you envision as a “sufficient” ethics requirement for Computer Science majors?
2. Describe two successful and two unsuccessful ways of teaching or incorporating ethics in Computer Science.
3. Provide a brief overview of a case study on embedding ethics into a Computer Science curriculum that you read. What insights and lessons can we draw from it?