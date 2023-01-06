---
permalink: /modules/algorithms/misinformation/
layout: home
title: Propaganda and Misinformation
parent: Algorithmic Decision-Making
nav_order: 2
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Reading Responses</h2>
Please answer the following three questions using 150 words or less for each response:

1. Recall the following formula that Facebook uses in their News Feed ranking algorithm: 

>V<sub>ijt</sub> = w<sub>ijt1</sub>Y<sub>ijt1</sub> + w<sub>ijt2</sub>Y<sub>ijt2</sub> + … + w<sub>ijtk</sub>Y<sub>ijtk</sub>

where

> Y<sub>ijt</sub> = f(x<sub>ijt1</sub>; x<sub>ijt2</sub>; … x<sub>ijtC</sub>)
>
> X<sub>it</sub> = [x<sub>ijt1</sub>; x<sub>ijt2</sub>; …, x<sub>ijtc</sub>, ..., x<sub>ijt(C-1)</sub>, x<sub>ijtC</sub>].

Briefly explain what each of the following variables in the formula stand for and provide examples (if applicable) for values the variable might take: *V, Y, X, w, k, x, c, j, t, f*?

Note that *f(...)* is a formula, the notation *A = [1, 2, 3]* refers to some vector A containing the elements *{1, 2, 3}*, and *i* is an integer that refers to some post i.

{:style="counter-reset:none"}
2. Imagine that you come across a suspicious post while browsing the social media platform of your choice. Please explain how you would decide whether or not the post contains accurate information.

In your answer, make sure to explicitly list the factors or signals that you would rely on when making the determination. For instance, the platform where you came across the post is an example of a factor/signal that you might use. 

{:style="counter-reset:none"}
3. List three different, distinct solutions to the problem of misinformation on social media platforms.

In writing your response, please refer to the assigned readings. A complete response to each question is worth 1 point.