---
permalink: /modules/algorithms/misinformation/
layout: home
title: Propaganda and Misinformation
parent: Algorithmic Decision-Making
nav_order: 2
readings:
    - "Verizon, [\"A Guide to Misinformation: How to Spot and Combat Fake News\"](https://web.archive.org/web/20201226045612/https://www.verizon.com/info/technology/fake-news-on-social-media/), 2020."
    - "Akos Lada, Meihong Wang, Tak Yan, [\"How machine learning powers Facebook's News Feed ranking algorithm\"](https://engineering.fb.com/2021/01/26/ml-applications/news-feed-ranking/), 2021."
    - "Karen Hao, [\"The Facebook whistleblower says its algorithms are dangerous. Here's why.\"](https://www.technologyreview.com/2021/10/05/1036519/facebook-whistleblower-frances-haugen-algorithms/), 2021."
    - "Chris Meserole, [\"How misinformation spreads on social media—And what to do about it\"](https://www.brookings.edu/blog/order-from-chaos/2018/05/09/how-misinformation-spreads-on-social-media-and-what-to-do-about-it/), 2018."
    - "Filippo Menczer and Thomas Hills, [\"Information Overload Helps Fake News Spread, and Social Media Knows It\"](https://www.scientificamerican.com/article/information-overload-helps-fake-news-spread-and-social-media-knows-it/), 2020."
    - "(Skim) The Wall Street Journal, [\"How to Fix Social Media\"](https://www.wsj.com/articles/how-to-fix-social-media-11635526928), 2021."
    - "(Skim) Renée DiResta, [\"It's Not Misinformation. It's Amplified Propaganda\"](https://www.theatlantic.com/ideas/archive/2021/10/disinformation-propaganda-amplification-ampliganda/620334/), 2021."
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