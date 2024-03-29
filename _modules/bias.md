---
permalink: /modules/algorithms/bias/
layout: home
title: Bias and Fairness
parent: Algorithmic Decision-Making
nav_order: 1
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>

1. Name at least three factors that introduce or contribute to bias in algorithms and machine-learning models used in decision-making. What proposed solutions exist to eliminate or mitigate the factors that lead to such bias?
2. Recall the [Machine Bias article](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing). Why did ProPublica argue that the COMPAS algorithm is biased against black defendants? How did Northpointe, the developer of the algorithm, respond to this criticism according to the [Washington Post's article](https://www.washingtonpost.com/news/monkey-cage/wp/2016/10/17/can-an-algorithm-be-racist-our-analysis-is-more-cautious-than-propublicas)?