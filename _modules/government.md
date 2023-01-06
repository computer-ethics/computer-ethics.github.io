---
permalink: /modules/policy/government/
layout: home
title: Government and Technology
parent: Technology Law and Policy
nav_order: 2
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>
1. Do you think there should be a centralized agency that handles technology delivery?
2. What challenges do you think could arise while working in government and how do you think they could be overcome?
3. If you were to join government as a career technologist, what would you change?
