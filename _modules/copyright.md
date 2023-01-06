---
permalink: /modules/policy/copyright/
layout: home
title: Intellectual Property, Copyright, and Patents
parent: Technology Law and Policy
nav_order: 1
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Reading Responses</h2>
Please answer the following two questions using 150 words or less for each response:

1. Explain the issues that exist around software patents and provide at least one argument in their favor. 
2. In your own words, explain what the Digital Millennium Copyright Act (DMCA) is. What are the implications of DMCA for computer scientists and software developers? 
3. Proponents of open-source software often invoke “Linus’s Law,” or the idea that with enough people looking at some code "[all bugs become shallow](https://www.microsoft.com/en-us/security/blog/2006/06/07/linuss-law-aka-many-eyes-make-all-bugs-shallow/).” Do you personally agree with that statement? Provide at least one counter-argument against Linus’s Law. 

In writing your response, please refer to the assigned readings and your personal experiences. A complete response to each question is worth 1 point. 

<h2 class="text-delta">Discussion Questions</h2>
1. Why, according to some critics, is the software patent system "broken"? Describe at least one proposed solution to fix the "broken" software patent system.
2. Provide a brief overview of the Digital Millennium Copyright Act (DMCA). Why is DMCA often considered to be controversial?
3. What are some of the advantages of open-source software versus closed-source? What are the disadvantages? Where do you personally stand on this debate?