---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech in Computer Science and Engineering, IIT Gandhinagar, 2024 (expected)

Work experience
======
- **DE Shaw**, hyderabad, software development intern *[May-June 2023]*
  - Developed generalized ETL (extract, transform and load) pipeline to cover as many different data formats as possible to decrease workload of a team. Now they don't need to develop script for every different cases.
  - Load data from csv to sql tables. CSV files comes in AWS S3 bucket and should be loaded in AWS Redshift. Learned both of the infrastrctures.
  - Used python to develop the whole software. Developed highly scalable and maintainable software. Wrote unittests to ease out work for other members.
  
Skills
======
* Problem solving, Competitive programming
* Software development enginnering
  * Machine Learning
  * Software Development
  * System Programming
* Communication, Leadership
  
Projects
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
