---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

{% include cv-template.html %}

<style>
  .cv-profile-header { margin-bottom: 1.5em; }
  .cv-profile-header h2 { margin-bottom: 0.1em; }
  .cv-profile-bio { margin: 0.3em 0 0.6em; }
  .cv-profile-meta, .cv-profile-links { list-style: none; margin: 0; padding: 0; }
  .cv-profile-meta li, .cv-profile-links li { display: inline-block; margin: 0 1em 0.4em 0; }
</style>

<div class="cv-profile-header">
  <h2>{{ site.author.name }}</h2>
  {% if site.author.bio %}<p class="cv-profile-bio">{{ site.author.bio }}</p>{% endif %}

  <ul class="cv-profile-meta">
    {% if site.author.employer %}<li><i class="fas fa-fw fa-building-columns"></i> {{ site.author.employer }}</li>{% endif %}
    {% if site.author.location %}<li><i class="fas fa-fw fa-location-dot"></i> {{ site.author.location }}</li>{% endif %}
    {% if site.author.email %}<li><i class="fas fa-fw fa-envelope"></i> <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></li>{% endif %}
  </ul>

  <ul class="cv-profile-links">
    {% if site.author.googlescholar %}<li><a href="{{ site.author.googlescholar }}" target="_blank">Google Scholar</a></li>{% endif %}
    {% if site.author.orcid %}<li><a href="{{ site.author.orcid }}" target="_blank">ORCID</a></li>{% endif %}
    {% if site.author.github %}<li><a href="https://github.com/{{ site.author.github }}" target="_blank">GitHub</a></li>{% endif %}
    {% if site.author.linkedin %}<li><a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank">LinkedIn</a></li>{% endif %}
  </ul>
</div>

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>

<!-- <div class="wordwrap">You can also find my CV <a href="files/CV_Spring_2026.pdf">here</a>.</div> -->

Education
======
* Ph.D in Linguistics, Stanford University, 2031 (expected)
* M.S. in Computer Science, Brown University, 2026
* B.S. in Mathematics and Computer Science, Brown University, 2025
* B.A. in Linguistics, Brown University, 2025

Research Experience: CS & Math
======
* 2025-2026: Brown LUNAR Lab
  * Test the causal faithfulness of the reasoning tokens and latent reasoning of LLMs
  * Find limitations intervention methodologies for CoT reasoning steps
* Summer 2025: Center for Human-Compatible AI
  * Examined how LLMs internally organize factual knowledge into entities and properties through mechanistic interpretability, contributing to the recent literature on LLM factual recall
  * Built tools to examine and modify LLM’s knowledge structure for safer AI
* Summer 2023: Brown University
  * Formulated and proved lemmas on the existence of periodic billiard paths for Ideal Hyperbolic Quadrilaterals under regular Euclidean billiard rules by creating simulation programs with Python
  * Informally shared work at Mathematikon in Heidelberg, Germany
* 2020-2022Johns Hopkins University
  * Proved a theorem on random graphs that entropy is the upper bound of the graph’s heterogeneity coefficient, starting a research project on a new information metric applicable to Information Theory and Machine Learning

Research Experience: Linguistics & Others
======
* 2024-2025: Brown University
  * Analyzed discourse anaphors to propositions and events that involve epistemic uncertainty
  * Extended a previous dynamic semantics framework to cover conditionals
  * Delivered a talk as one of the 10 main sessions in a top conference

* 2024-2025: Center for Digital Scholarship at Brown University
  * Designed a pipeline using AI models to automate data inconsistency detection, helping publicize records and experiences of enslaved Native Americans
  * Created a program involving AI that generates XML-tagged archival data from raw pdf inscription files, resolving a research bottleneck and making archival data more accessible to the public
  * Developed a framework to develop metrics for AI generated outputs that do not have corresponding ground truth labels

* 2024: Brown Language and Thought Lab
  * Recruited participants and conducted studies for experiments designed by PhD students
  * Created stimuli for language acquisition experiments using JavaScript and React
  * Automated a data pipeline to gather and process data for 500+ children born across Rhode Island each month for research participant outreach, minimizing hours of manual work for the lab

Writing & Communication
=====
* 2025: The Prospector
  * Published an essay, *The Unbearable Lightness of Reading* on a Comparative Literature journal, giving structural analysis of a novel by Milan Kundera that maps the narrative plot to linguistic and cognitive structures
  * Accepted and edited submissions for publication
* 2025: Polyglot
  * Published a translation of the iconic Avant-Garde poem *Un coup de Des* into Korean
* 2023-2024: A Priori
  * Managed the operations and publication of an undergraduate philosophy journal at Brown University
* 2022-2023: Intercollegiate Finance Journal
  * Published an article about the future trends in sustainable finance
  * Managed and automated submission outreach to dozens of schools
* 2022-2023: Future of Sustainable Investment Conference
  * Planned and coordinated an annual sustainable finance conference with over 27 speakers and 200 attendees as a member of the strategy team, by selecting speaker topics, allocating the budget, and handling logistics before and during the conference


Leadership and Service
=====
* 2023-2026: Brown AI Safety Team
  * Lead an AI safety student group with educational programs, reading groups, workshops, and policy projects
* 2023-2024: Alpha Delta Phi
  * Hosted community service trips to local organizations such as the Rhode Island Community Food Bank and Mathewson St. Church soup kitchen
* 2023-2026: Housing Opportunities for People Everywhere
  * Participated in weekly research, political campaigns, and community education to help pass affordable housing laws in Provience, RI
  * Sourced and delivered food, hygiene products, and necessities, and found temporary housing for people in need


Skills
======
* Computer Languages: Python, Java, C, R, JavaScript, MATLAB, SQL
* Natural Languages: Korean (native), Italian, French, Mandarin (conversational), Latin, Greek (reading)

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
