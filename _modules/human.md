---
permalink: /modules/privacy/human/
layout: home
title: Human Factors
parent: Privacy, Surveillance, and Free Speech
nav_order: 3
readings:
    - "Alessandro Acquisti, Laura Brandimarte, and George Loewenstein, [\"Privacy and human behavior in the age of information\"](https://www.science.org/doi/10.1126/science.aaa1465), 2015."
    - "Ivano Bongiovanni, Karen Renaud, and Noura Aleisa, [\"The privacy paradox: we claim we care about our data, so why don't our actions match?\"](https://theconversation.com/the-privacy-paradox-we-claim-we-care-about-our-data-so-why-dont-our-actions-match-143354), 2020."
    - "Arielle Pardes, [\"How Facebook and Other Sites Manipulate Your Privacy Choices\"](https://www.wired.com/story/facebook-social-media-privacy-dark-patterns/), 2020."
    - "Genia Kostka, [\"What do people in China think about 'social credit' monitoring?\"](https://www.washingtonpost.com/politics/2019/03/21/what-do-people-china-think-about-social-credit-monitoring/), 2019."
    - "(Skim) Institute of Global Health Innovation (IGHI), [\"Covid-19: Perceptions of Contact Tracing Global Report\"](https://www.imperial.ac.uk/media/imperial-college/institute-of-global-health-innovation/Global_ICL-YouGov-Covid-19-Behaviour-Tracker_contact-tracing_20200821_vF%5B1%5D.pdf), 2020."
    - "(Skim, skip chapter 4) Laura Brandimarte and Alessandro Acquisti, [\"The Economics of Privacy\"](https://academic.oup.com/edited-volume/28259/chapter-abstract/213408789?redirectedFrom=fulltext), 2012."
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign module = site.readings | where:"permalink", page.permalink  | first %}
{% assign sorted_readings = module.readings | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Reading Responses</h2>
The assigned readings for this week discuss cultural and individual factors that impact our attitudes towards privacy and surveillance.

Please answer the following three questions using 150 words or less for each of your responses:
1. What is the “privacy paradox” and what are some possible ways to mitigate its consequences?
2. How do perceptions and attitudes towards surveillance vary across different countries?
3. What are some examples of dark patterns that you have encountered and how did they affect your interactions with the app, service, website, etc.? 

In writing your response, please refer to the assigned readings and your personal experiences. A complete response to each question is worth 1 point (out of 3 in total).

<h2 class="text-delta">Discussion Questions</h2>

1. Consider the strategies that one might adopt to preserve their privacy: using a VPN, having long passwords, reading privacy policies, etc. Should it be our responsibility to take these actions to ensure our privacy is protected? If yes, then why? If not, then whose responsibility should it be?
2. Imagine that you are employed at ShadyTech, LLC and they ask you to design a product that would maximize their profits through careful UI design. What dark patterns you might employ to achieve this? For each pattern, describe the dark pattern and its intended impact on user behavior. 
3. Recall the reading describing the attitudes of people in China towards ‘social credit’ monitoring. If a similar scoring system were proposed in the US, how might the attitude of the American public be different and how might it be similar? In responding to this question, feel free to draw parallels with existing scoring systems used in the US. 