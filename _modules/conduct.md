---
permalink: /modules/ethics/conduct/
layout: home
title: Professional Conduct
parent: Ethics and Values
nav_order: 1
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Reading Responses</h2>
Please answer the following two questions using 150 words or less for each response:
1. The article “Feynman’s Error: On Ethical Thinking and Drifting” raises a concern about “the way our lives and communities are shaped “by drift and inadvertence.”” In your own words, describe what the moral problem of “drift and inadvertence” is and how it can be addressed. 
2. Consider an online service, website, social network, platform, app, or any other technology of your choosing. Which “risk zones” from the “Risk Mitigation Checklist” are the most relevant to the technology that you chose and why?

In writing your response, please refer to the assigned readings and your personal experiences. A complete response to each question is worth 1 point.

<h2 class="text-delta">Discussion Questions</h2>

1. Recall the ACM Code of Ethics and Professional Conduct and the Risk Mitigation Checklist by Ethical OS. Choose a company or an organization in the tech industry and describe at least three ways in which it violates the principles laid out in those documents.
2. Do you believe that Feynman was valid in his thinking that “the creation of an atomic bomb was inevitable, so the US may as well make it first”?
3. Provide a brief overview of a case study that you read. What insights and lessons can we draw from it in order to prevent similar accidents and ethics violations in the future? 