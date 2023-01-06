---
permalink: /modules/software/attention/
layout: home
title: Attention and Engagement
parent: Software Risks and Case Studies
nav_order: 2
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Reading Responses</h2>
Please answer the following three questions using 150 words or less for each response:

1. In your words, explain what “persuasive technology” is. What are the benefits and what are the dangers of products that use persuasive design patterns?

2. In his TED Talk, Nir Eyal says: 
>*“…what makes these products [such as Facebook or our iPhone] so engaging also makes them better. There is an entire world of products out there that failed to engage us because the product-makers don’t understand the psychology of good product design.”* 

Do you agree or disagree with this statement and why? 

{:style="counter-reset:none"}
3. Have you ever taken steps to reduce the time that you spend using your devices or specific apps? If yes, what approaches and tools did you use, and what was your experience? If not, what reasons prevented you from reducing the time spent using your devices and apps?

In writing your response, please refer to the assigned readings and your personal experiences. A complete response to each question is worth 1 point. 