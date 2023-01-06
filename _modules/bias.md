---
permalink: /modules/algorithms/bias/
layout: home
title: Bias and Fairness
parent: Algorithmic Decision-Making
nav_order: 1
readings:
    - "(Background) Mehran Sahami, [\"A Very Brief Introduction to Probability and Machine Learning with the Perceptron Algorithm\"](https://drive.google.com/file/d/1WXgpzCYU6GC7P1yBKhrMPjehdTz1Ghqd/view), 2021."
    - "Julia Angwin et al., [\"Machine Bias\"](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing), 2016."
    - "Julia Angwin, [\"Make Algorithms Accountable\"](https://www.nytimes.com/2016/08/01/opinion/make-algorithms-accountable.html), 2016."
    - "Sam Corbett-Davies et al., [\"A computer program used for bail and sentencing decisions was labeled biased against blacks. It's actually not that clear\"](https://www.washingtonpost.com/news/monkey-cage/wp/2016/10/17/can-an-algorithm-be-racist-our-analysis-is-more-cautious-than-propublicas/#comments), 2016."
    - "(Skim) Solon Barocas, Moritz Hardt, Arvind Narayanan, [\"Fairness and Machine Learning\"](https://fairmlbook.org/pdf/fairmlbook.pdf), 2022."
    - "(Explore) Karen Hao and Jonathan Stray, [\"Can you make AI fairer than a judge? Play our courtroom algorithm game\"](https://www.technologyreview.com/2019/10/17/75285/ai-fairer-than-judge-criminal-risk-assessment-algorithm/), 2019."
    - "(Explore) Martin Wattenberg et al., [\"Attacking discrimination with smarter machine learning\"](https://research.google.com/bigpicture/attacking-discrimination-in-ml/), 2016."
readings_objects:
    - title: "A Very Brief Introduction to Probability and Machine Learning with the Perceptron Algorithm"
      author: "Mehran Sahami"
      year: 2021
      url: "https://drive.google.com/file/d/1WXgpzCYU6GC7P1yBKhrMPjehdTz1Ghqd/view"
      note: "Background"

    - title: "Machine Bias"
      author: "Julia Angwin et al."
      year: 2016
      url: "https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing"
      note: ""

    - title: "Make Algorithms Accountable"
      author: "Julia Angwin"
      year: 2016
      url: "https://www.nytimes.com/2016/08/01/opinion/make-algorithms-accountable.html"
      note: ""

    - title: "A computer program used for bail and sentencing decisions was labeled biased against blacks. It's actually not that clear"
      author: "Sam Corbett-Davies et al."
      year: 2016
      url: "https://www.washingtonpost.com/news/monkey-cage/wp/2016/10/17/can-an-algorithm-be-racist-our-analysis-is-more-cautious-than-propublicas/"
      note: ""

    - title: "Fairness and Machine Learning"
      author: "Solon Barocas, Moritz Hardt, Arvind Narayanan"
      year: 2022
      url: "https://fairmlbook.org/pdf/fairmlbook.pdf"
      note: "Skim"

    - title: "Can you make AI fairer than a judge? Play our courtroom algorithm game"
      author: "Karen Hao and Jonathan Stray"
      year: 2019
      url: "https://www.technologyreview.com/2019/10/17/75285/ai-fairer-than-judge-criminal-risk-assessment-algorithm/"
      note: "Explore"

    - title: "Attacking discrimination with smarter machine learning"
      author: "Martin Wattenberg et al."
      year: 2016
      url: "https://research.google.com/bigpicture/attacking-discrimination-in-ml/"
      note: "Explore"
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign sorted_readings = page.readings_objects | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>

1. Name at least three factors that introduce or contribute to bias in algorithms and machine-learning models used in decision-making. What proposed solutions exist to eliminate or mitigate the factors that lead to such bias?
2. Recall the [Machine Bias article](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing). Why did ProPublica argue that the COMPAS algorithm is biased against black defendants? How did Northpointe, the developer of the algorithm, respond to this criticism according to the [Washington Post's article](https://www.washingtonpost.com/news/monkey-cage/wp/2016/10/17/can-an-algorithm-be-racist-our-analysis-is-more-cautious-than-propublicas)?