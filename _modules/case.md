---
permalink: /modules/software/case/
layout: home
title: Case Studies
parent: Software Risks and Case Studies
nav_order: 1
readings:
    - "Gregory Travis, [\"How the Boeing 737 MAX Disaster Looks to a Software Developer\"](https://spectrum.ieee.org/how-the-boeing-737-max-disaster-looks-to-a-software-developer), 2019."
    - "Spencer Woodman, [\"Palantir Provides the Engine for Donald Trump's Deportation Machine\"](https://theintercept.com/2017/03/02/palantir-provides-the-engine-for-donald-trumps-deportation-machine/), 2017."
    - "Phil Koopman, [\"A Case Study of Toyota Unintended Acceleration and Software Safety\"](https://ptolemy.berkeley.edu/projects/chess/pubs/1081/koopman14_toyota_ua_slides.pdf), 2014."
readings_objects:
    - title: "How the Boeing 737 MAX Disaster Looks to a Software Developer"
      author: "Gregory Travis"
      year: 2019
      url: "https://spectrum.ieee.org/how-the-boeing-737-max-disaster-looks-to-a-software-developer"
      note: ""

    - title: "Palantir Provides the Engine for Donald Trump's Deportation Machine"
      author: "Spencer Woodman"
      year: 2017
      url: "https://theintercept.com/2017/03/02/palantir-provides-the-engine-for-donald-trumps-deportation-machine/"
      note: ""

    - title: "A Case Study of Toyota Unintended Acceleration and Software Safety"
      author: "Phil Koopman"
      year: 2014
      url: "https://ptolemy.berkeley.edu/projects/chess/pubs/1081/koopman14_toyota_ua_slides.pdf"
      note: ""
---

# {{ page.title }}
<h2 class="text-delta">Readings</h2>
{% assign sorted_readings = page.readings_objects | sort: "year" | reverse %}
{% include get_readings.html readings=sorted_readings -%}

<h2 class="text-delta">Discussion Questions</h2>
1. Provide a brief overview of a case study that you read. What insights and lessons can we draw from it in order to prevent similar accidents and ethics violations in the future? 