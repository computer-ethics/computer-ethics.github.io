---
permalink: /modules/privacy/overview/
layout: home
title: Overview
parent: Privacy, Surveillance, and Free Speech
nav_order: 1
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>
1. What does “privacy” mean to you and when do you have a reasonable expectation of privacy?
2. Think about examples of surveillance that is enabled or assisted by computer technologies. What are the benefits and dangers of such surveillance? Please refer to specific examples of surveillance in your response.
3. Do you take any steps to protect your privacy online? Why or why not?