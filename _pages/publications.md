---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

title: "Under Review"

---
title: "“Feedback from the Machine”: The Influence of Automated Narrative Feedbackon Student-Designed Gamified Research"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-2
excerpt: 'In this paper, we investigate the impact of automatically-generated formative assessment on students’ design process and educationalexperience. University students learning about experimental design were tasked with creating virtual experiments using a narrativegame creation tool. We present the results of a mixed-methods study, conducted across two course sections, in which one coursesection received automated feedback on the structural and interactive aspects of their games’ narrative design, and the other sectiondid not. Our results reveal that students who received AI-generated feedback actively engaged with the feedback system, reflected onits provided suggestions, and evaluated the trade-offs in applying them. We further find that their projects developed more over timein regard to their narrative design. However, students had mixed responses to receiving feedback from an automated system, whichwe explore in this paper and use to make suggestions for future design and implementation of AI-based feedback systems.'

venue: 'CHI 2021: ACM Conference on Human Factors in Computing Systems'
---
