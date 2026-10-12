---
permalink: /
title: "About Marcus McAllister"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Introduction
------
Greetings! I am a Computer Science Ph.D. Student at the University of Maryland, Baltimore County co-advised by [Dr. Lara Martin](https://laramartin.net/) and [Dr. Cynthia Matuszek](https://userpages.cs.umbc.edu/cmat/). I am an active member in the [Interactive Robotics and Language (IRAL) lab](https://iral.cs.umbc.edu) as well as the [Language, Aid, and Representation AI (LARA) lab](https://laramartin.net/lab/) where I collaborate with other members to address human-machine accessibility challenges.

I am also a full-time senior software engineer at [Datanova Scientific, LLC](https://www.datanovascientific.com/) where I develop software solutions for use in the US federal government and private sector.

Research
------
I have broad interest in the domains of machine learning, artificial intelligence, natural language processing, robotics, data fusion, semantic web technology, and recommendation systems.

My current research focuses on AI-enhanced personalization of recommendation systems to enable both information-need discovery and improved user experience. Many contemporary information systems face bandwidth, storage, and processing challenges when deliverying information to users. Often, these systems categorize their users into a limited number of profile types to improve the relevance of information content. However, this can lead to specific data sources being recommended and prioritized over others simply due to broad appeal across all users despite not being relevant for a particular use case. By tailoring results to specific contexts, users can find the information most relevant and appealing for their usage.

Active Projects
------
These are the projects that I am actively engaged with at this time with intent towards publication.

{% include base_path %}

{% assign active_projects = site.projects | where: "status", "active" %}

{% if active_projects.size > 0 %}
{% for post in active_projects %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}
