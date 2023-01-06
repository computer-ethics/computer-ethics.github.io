---
permalink: /modules/ethics/conduct/
layout: home
title: Professional Conduct
parent: Ethics and Values
nav_order: 1
readings:
    - "ACM, [\"Code of Ethics and Professional Conduct\"](https://www.acm.org/code-of-ethics), 2018."
    - "Ethical OS, [\"Risk Mitigation Checklist\"](https://ethicalos.org/wp-content/uploads/2018/08/EthicalOS_Check-List_080618.pdf), 2018."
    - "Davide Castelvecchi, [\"Prestigious AI meeting takes steps to improve ethics of research\"](https://www.nature.com/articles/d41586-020-03611-8), 2020."
    - "Dan Munro, [\"Feynman's Error: On Ethical Thinking and Drifting\"](https://www.danmunro.ca/blog/2018/11/29/feynmans-error-on-ethical-thinking-and-drifting-nbsp), 2018."
    - "(Skim) Helen Nissenbaum, [\"Accountability in a computerized society\"](https://link.springer.com/article/10.1007/BF02639315), 1996."
readings_objects:
    - title: "Code of Ethics and Professional Conduct"
      author: "ACM"
      year: 2018
      url: "https://www.acm.org/code-of-ethics"
      note: ""

    - title: "Risk Mitigation Checklist"
      author: "Ethical OS"
      year: 2018
      url: "https://ethicalos.org/wp-content/uploads/2018/08/EthicalOS_Check-List_080618.pdf"
      note: ""

    - title: "Prestigious AI meeting takes steps to improve ethics of research"
      author: "Davide Castelvecchi"
      year: 2020
      url: "https://www.nature.com/articles/d41586-020-03611-8"
      note: ""

    - title: "Feynman's Error: On Ethical Thinking and Drifting"
      author: "Dan Munro"
      year: 2018
      url: "https://www.danmunro.ca/blog/2018/11/29/feynmans-error-on-ethical-thinking-and-drifting-nbsp"
      note: ""

    - title: "Accountability in a computerized society"
      author: "Helen Nissenbaum"
      year: 1996
      url: "https://link.springer.com/article/10.1007/BF02639315"
      note: "Skim"
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign sorted_readings = page.readings_objects | sort: "year" | reverse %}
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