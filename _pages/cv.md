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
* B.A. Chemistry, University of Rochester, 2007
* Ph.D in Molecular Medicine, Case Western Reserve University, 2013 

Work experience
======
* 2018-2019: 
  * Genomic Prediction
  * Developed fingerprinting on sparse and noisy dataset across a diverse set
    of sequencing technologies and methodologies and integrated with cloud
    pipeline for client reports.  In a short timeframe, came up with and
    implemented an out of sample validation for a T1D preditor in a large
    sibling cohort, a critical component of the flagship product.  Part of team
    that developed relative risk model for embryo selection.

* 2013-2018 Postdoctoral Researcher
  * Cleveland Clinic Foundation
  * Large RNA-sequencing project studying the genetic control of gene
    expression in heart tissues.  Project required a HPC-pipeline for
    quantifying transcripts levels.  Discovered several long non-coding RNAs that are under genetic control and have potential to influcence heart disease risk.  

  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
