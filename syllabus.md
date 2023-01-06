---
permalink: /syllabus/
layout: home
title: Syllabus
nav_order: 2
---

# Sample Syllabus
{: .no_toc }

This page presents the syllabus, assignments, and their grade contribution used to teach the advanced discussion section of the UC Berkeley’s semester-long CS195 course [(Social Implications of Computer Technology)](https://www2.eecs.berkeley.edu/Courses/CS195/) in Fall 2021. You are free to use this syllabus as is or modify it better to suit your teaching needs.

## Table of contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Schedule
{% assign ethics = site.modules | where:"permalink", "/modules/ethics/"  | first %}
{% assign conduct = site.readings | where:"permalink", "/modules/ethics/conduct/"  | first %}
{% assign education = site.readings | where:"permalink", "/modules/ethics/education/"  | first %}

{% assign privacy = site.modules | where:"permalink", "/modules/privacy/"  | first %}
{% assign overview = site.readings | where:"permalink", "/modules/privacy/overview/"  | first %}
{% assign vulnerable = site.readings | where:"permalink", "/modules/privacy/vulnerable/"  | first %}
{% assign human = site.readings | where:"permalink", "/modules/privacy/human/"  | first %}

{% assign software = site.modules | where:"permalink", "/modules/software/"  | first %}
{% assign case = site.readings | where:"permalink", "/modules/software/case/"  | first %}
{% assign attention = site.readings | where:"permalink", "/modules/software/attention/"  | first %}

{% assign algorithms = site.modules | where:"permalink", "/modules/algorithms/"  | first %}
{% assign bias = site.readings | where:"permalink", "/modules/algorithms/bias/"  | first %}
{% assign misinformation = site.readings | where:"permalink", "/modules/algorithms/misinformation/"  | first %}

{% assign policy = site.modules | where:"permalink", "/modules/policy/"  | first %}
{% assign copyright = site.readings | where:"permalink", "/modules/policy/copyright/"  | first %}
{% assign government = site.readings | where:"permalink", "/modules/policy/government/"  | first %}

| Module                                               | Topic                                                        | Assigned Materials                                                                                            |
|:-----------------------------------------------------|:-------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------|
| N/A                                                  | Introduction and Logistics                                   | N/A                                                                                                           |
| [{{ ethics.title }}]({{ ethics.permalink }})         | [{{ conduct.title }}]({{ conduct.permalink }})               | {% for reading in conduct.readings %}        * {% include get_reading.html reading=reading %}<br>{% endfor %} | 
| [{{ ethics.title }}]({{ ethics.permalink }})         | [{{ education.title }}]({ education.permalink })             | {% for reading in education.readings %}      * {% include get_reading.html reading=reading %}<br>{% endfor %} |
| [{{ privacy.title }}]({{ privacy.permalink }})       | [{{ overview.title }}]({{ overview.permalink }})             | {% for reading in overview.readings %}       * {% include get_reading.html reading=reading %}<br>{% endfor %} |
| [{{ privacy.title }}]({{ privacy.permalink }})       | [{{ vulnerable.title }}]({{ vulnerable.permalink }})         | {% for reading in vulnerable.readings %}     * {% include get_reading.html reading=reading %}<br>{% endfor %} |
| [{{ privacy.title }}]({{ privacy.permalink }})       | [{{ human.title }}]({{ human.permalink }})                   | {% for reading in human.readings %}          * {% include get_reading.html reading=reading %}<br>{% endfor %} |
| [{{ software.title }}]({{ software.permalink }})     | [{{ case.title }}]({{ case.permalink }})                     | {% for reading in case.readings %}           * {% include get_reading.html reading=reading %}<br>{% endfor %} |
| [{{ software.title }}]({{ software.permalink }})     | [{{ attention.title }}]({{ attention.permalink }})           | {% for reading in attention.readings %}      * {% include get_reading.html reading=reading %}<br>{% endfor %} |
| [{{ algorithms.title }}]({{ algorithms.permalink }}) | [{{ bias.title }}]({{ bias.permalink }})                     | {% for reading in bias.readings %}           * {% include get_reading.html reading=reading %}<br>{% endfor %} |
| [{{ algorithms.title }}]({{ algorithms.permalink }}) | [{{ misinformation.title }}]({{ misinformation.permalink }}) | {% for reading in misinformation.readings %} * {% include get_reading.html reading=reading %}<br>{% endfor %} |          
| [{{ policy.title }}]({{ policy.permalink }})         | [{{ copyright.title }}]({{ copyright.permalink }})           | {% for reading in copyright.readings %}      * {% include get_reading.html reading=reading %}<br>{% endfor %} |       
| [{{ policy.title }}]({{ policy.permalink }})         | [{{ government.title }}]({{ government.permalink }})         | {% for reading in government.readings %}     * {% include get_reading.html reading=reading %}<br>{% endfor %} |         
| N/A                                                  | Conclusion and Wrap-up                                       | N/A                                                                                                           |       

## Assessment

In addition to attending the regular weekly lecture, students participate in weekly discussions and write reading responses, lead discussions and prepare presentations informed by their understanding of the material, and engage in a series of experiential and real-world assignments.

1. **Attendance and Discussion Participation** (10%)
2. **Reading Responses** (10%)

Students are expected to demonstrate their understanding of weekly readings by submitting responses to questions based on the assigned material. Reading responses are due each week before the start of the discussion. Students assigned to lead the discussion are not required to submit the reading response for that week (more information below). 

{:style="counter-reset:none"}
3. **Discussion Leadership** (20%)

Each week, we will assign a student to lead the discussion based on the material for that week. Discussion leaders will also prepare a 10-minute presentation, which they will present to the class at the beginning of the session. Finally, students assigned to lead the discussion are expected to come up with a set of questions, shared with other students 24 hours before the class, used to foster the discussion around the presented material. We strongly encourage you to participate in office hours the week of your discussion leadership.

If you are one of the discussion leaders for a class, your primary responsibility is to identify and examine the central point of the reading. Your discussion and presentation should be structured around an exploration of the following questions:

* What is the central point of the reading? What are the authors trying to say?
* What did you learn from this reading?
* How do the authors make their case?
* How does the reading relate to the theme of the class?

Whether or not you’re the discussion leader, think about these questions as you read and as you prepare for class. Resist the temptation to focus on whether you agree or disagree with the author. Focus instead on the ideas the author is articulating and what you can learn from them.

{:style="counter-reset:none"}
4. **Assignments** (15% for each, 60% in total)

Students will complete 4 assignments that focus on the practical implications of the topics covered in this class. Some of these projects will be technical in nature, while others will assess your writing and analytical skills. 

[*Assignment 1: Surveillance, Privacy, and Free Speech*](/modules/privacy/assignments/#assignment-1-user-interviews)

For this assignment, you will be asked to come up with a set of requirements for a fictional app that aims to address a given real-world issue concerning the right to privacy and free speech. As part of this assignment, you will conduct at least two interviews with prospective users of the app, paying special attention to the use cases, desired functionality, and concerns brought up by the interviewees. 

You will summarize the interview findings in a short report, describe the main functional requirements of the app, and provide general recommendations to the app developers on how to implement this functionality while respecting user privacy and the right to free speech. 

In order to balance the workload, we will form pairs of students to complete this assignment.

[*Assignment 2: Ethics and Technology*](/modules/ethics/assignments/#assignment-1-critical-analysis-and-argumentation)

You must pick an article that describes a computer technology (e.g. a platform, an app, an algorithm, etc.) that presents a moral dilemma when considering its intended or unintended use cases. You must select an article from a reputable media source, a newspaper, a science or engineering journal or magazine, a specialized journal or magazine from a different discipline, or similar. 

In your paper, you will be asked to identify the moral dilemma and the ethical considerations of using this technology, explaining its benefits and dangers. You will then provide 2-3 independent, persuasive arguments for using the technology and 2-3 arguments against its use. Based on your arguments, you will provide a recommendation as to whether this technology should be used (explaining how to mitigate the potential dangers) or not (explaining how to achieve similar benefits in another way). In drawing your conclusion, be sure to explain which actors should have a say in how this technology is distributed, employed, and regulated.

You will need to complete this assignment individually.

*Assignment 3: Software Risks and Algorithmic Bias*

In this assignment, you will obtain experience developing a machine learning algorithm and assessing the resulting model on a number of criteria. Your investigation will include not only being able to transparently see the code for the machine learning algorithm (which is what some lawmakers argue is a necessary safeguard in deploying algorithms for such decision-making), but also assessing the “fairness” of the model produced by the algorithm on a number of criteria. You will be asked to determine what you would do to make the decision-making model produced by the algorithm more “fair,” and justify this position in a short writeup. 

In order to balance the workload, we will form pairs of students to complete this assignment and ensure that at least one team member has prior programming experience.

*Assignment 4: Final Reflection*

In this assignment you will be asked to write a final reflection essay using the provided prompt.

You will need to complete this assignment individually.

