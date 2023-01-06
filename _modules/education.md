---
permalink: /modules/ethics/education/
layout: home
title: Teaching Ethics
parent: Ethics and Values
nav_order: 2
readings:
    - "(Watch) MIT, [\"Teaching Ethics and Policy in Computer Science\"](https://www.youtube.com/watch?v=Kc2WbkDpQQc), 2019."
    - "Shashi Krishna, [\"Teaching Ethical Computing\"](https://computethought.blog/2020/04/26/teaching-ethical-computing/), 2020."
    - "Kay G. Schulze and Frances S. Grodzinsky, [\"Teaching ethical issues in computer science: what worked and what didn't\"](https://dl.acm.org/doi/10.1145/236462.236517), 1996."
    - "Jimmy Wu, [\"Optimize What?\"](https://communemag.com/optimize-what/), 2019."
    - "Paul Karoff, [\"Embedding ethics in computer science curriculum\"](https://news.harvard.edu/gazette/story/2019/01/harvard-works-to-embed-ethics-in-computer-science-curriculum/), 2019."
    - "Tom Abate, [\"How the Computer Science Department is teaching ethics to its students\"](https://engineering.stanford.edu/magazine/how-computer-science-department-teaching-ethics-its-students), 2020."
    - "Robert Florida, [\"Weaving Ethics Into Columbia's Computer Science Curriculum\"](https://science.fas.columbia.edu/news/weaving-ethics-into-columbias-computer-science-curriculum/), 2019."
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