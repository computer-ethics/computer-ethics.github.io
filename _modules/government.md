---
permalink: /modules/policy/government/
layout: home
title: Government and Technology
parent: Technology Law and Policy
nav_order: 2
readings:
    - "Kim Zetter, [\"Of Course Congress Is Clueless About Tech—It Killed Its Tutor\"](https://www.wired.com/2016/04/office-technology-assessment-congress-clueless-tech-killed-tutor/), 2016."
    - "Frank Nagle, [\"Digital infrastructure is more than just broadband: What the US can learn from Europe's open source technology policy study\"](https://www.brookings.edu/research/digital-infrastructure-is-more-than-just-broadband-what-the-u-s-can-learn-from-europes-open-source-technology-policy-study/), 2021."
    - "Dante Disparte and Tomicah Tillemann, [\"To Move Forward, Federal IT Infrastructure Needs Resiliency\"](https://fedtechmagazine.com/article/2021/02/move-forward-federal-it-infrastructure-needs-resiliency), 2021."
    - "Brian Naylor, [\"'The Fifth Risk' Paints A Portrait Of A Government Led By The Uninterested\"](https://www.npr.org/2018/10/02/652563904/the-fifth-risk-paints-a-portrait-of-a-government-led-by-the-uninterested), 2018."
    - "Technology and Operations Management at Harvard University, [\"The Failed Launch Of www.HealthCare.gov\"](https://d3.harvard.edu/platform-rctom/submission/the-failed-launch-of-www-healthcare-gov/), 2016."
    - "(Skim) Kearney, [\"IT infrastructure: pillar of digital government\"](https://www.kearney.com/public-sector/article/-/insights/it-infrastructure-pillar-of-digital-government), 2015." 
readings_objects:
    - title: "Of Course Congress Is Clueless About Tech—It Killed Its Tutor"
      author: "Kim Zetter"
      year: 2016
      url: "https://www.wired.com/2016/04/office-technology-assessment-congress-clueless-tech-killed-tutor/"
      note: ""

    - title: "Digital infrastructure is more than just broadband: What the US can learn from Europe's open source technology policy study"
      author: "Frank Nagle"
      year: 2021
      url: "https://www.brookings.edu/research/digital-infrastructure-is-more-than-just-broadband-what-the-u-s-can-learn-from-europes-open-source-technology-policy-study/"
      note: ""

    - title: "To Move Forward, Federal IT Infrastructure Needs Resiliency"
      author: "Dante Disparte and Tomicah Tillemann"
      year: 2021
      url: "https://fedtechmagazine.com/article/2021/02/move-forward-federal-it-infrastructure-needs-resiliency"
      note: ""

    - title: "'The Fifth Risk' Paints A Portrait Of A Government Led By The Uninterested"
      author: "Brian Naylor"
      year: 2018
      url: "https://www.npr.org/2018/10/02/652563904/the-fifth-risk-paints-a-portrait-of-a-government-led-by-the-uninterested"
      note: ""

    - title: "The Failed Launch Of www.HealthCare.gov"
      author: "Technology and Operations Management at Harvard University"
      year: 2016
      url: "https://d3.harvard.edu/platform-rctom/submission/the-failed-launch-of-www-healthcare-gov/"
      note: ""

    - title: "IT infrastructure: pillar of digital government"
      author: "Kearney"
      year: 2015
      url: "https://www.kearney.com/public-sector/article/-/insights/it-infrastructure-pillar-of-digital-government"
      note: "Skim"
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign sorted_readings = page.readings_objects | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>
1. Do you think there should be a centralized agency that handles technology delivery?
2. What challenges do you think could arise while working in government and how do you think they could be overcome?
3. If you were to join government as a career technologist, what would you change?
