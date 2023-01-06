---
permalink: /modules/privacy/overview/
layout: home
title: Overview
parent: Privacy, Surveillance, and Free Speech
nav_order: 1
readings:
    - "Andrew Yang, [\"Op-Ed by Andrew Yang: Make tech companies pay you for your data\"](https://www.latimes.com/opinion/story/2020-06-23/andrew-yang-data-dividend-tech-privacy), 2020."
    - "Louis Menand, [\"Why Do We Care So Much About Privacy?\"](https://www.newyorker.com/magazine/2018/06/18/why-do-we-care-so-much-about-privacy), 2018."
    - "Douglas MacMillan and Nick Anderson, [\"Student tracking, secret scores: How college admissions offices rank prospects before they apply\"](https://www.washingtonpost.com/business/2019/10/14/colleges-quietly-rank-prospective-students-based-their-personal-data/), 2019."
    - "Jack Poulson, [\"I Used to Work for Google. I Am a Conscientious Objector.\"](https://www.nytimes.com/2019/04/23/opinion/google-privacy-china.html), 2019."
    - "BBC News, [\"Microsoft says error caused 'Tank Man' Bing censorship\"](https://www.bbc.com/news/world-asia-57367100), 2021."
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