---
permalink: /modules/software/case/
layout: home
title: Case Studies
parent: Software Risks and Case Studies
nav_order: 1
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>
1. Provide a brief overview of a case study that you read. What insights and lessons can we draw from it in order to prevent similar accidents and ethics violations in the future? 