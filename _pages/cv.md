---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /courses/
  - /achievements/
---

{% include base_path %}

The PDF version of my CV can be downloaded [here](/files/Resume_Research.pdf).

Education
======
* Ph.D. in Computer Science, University of Massachusetts Amherst, 2021 - present
  * Doing research in graph algorithms
  * Advisor: [Dr. Hung Le](https://hunglvosu.github.io) 
* M.S. in Computer Science, University of Nebraska - Lincoln, 2021
  * CPA: 4.0
* B.S. in Computer Science, Hanoi University of Science and Technology, 2019
  * CPA: 3.69 (rank 1st in the honor class)
  * Major CPA: 3.92

Publications
======
  <ul>{% assign cv_pubs = site.publications | sort: "date" | reverse %}{% for post in cv_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work experience
======
* Summer 2023: Student Researcher at Google Research
  * Design and Implement graph based sampling algorithm for LLM
    
* Summer 2021 - present: Research Assistant
  * University of Massachusetts Amherst
  * Design algorithm finding sublinear separators in greedy spanners.
  * Mentor students in [Early Research Scholars Program](https://sites.google.com/umass.edu/ersp-cics). Assist them in reading papers, formalizing and developing ideas for theoretical problems.

* Fall 2019: Research Assistant
  * Computational Decision Science Lab, University of Nebraska - Lincoln
  * Project: Schelling games on graphs
 
* Fall 2017 - Spring 2019: Research Assistant
  * MSO Lab, Hanoi University of Science and Technology
  * Project: Algorithms solving the maximal induced matching in perfect graphs
  
Skills
======
 * Languages & technology: Proficient in C, C++, Java. Previously used Python, MATLAB, C#, SQL, JavaScript and Ocaml.
 * Experience with Unix/Linux, macOS, Windows.
 
Honors and Awards
======
*	Google Ph.D. Fellowship in Algorithms & Optimization, 2025.
*	Passed the Ph.D. Qualifying Exam with distinction, University of Massachusetts Amherst, 2025.
*	First place in ICPC North Central North America Regional Contest 2019.
*	Rank 6th (Second Prize) in ACM ICPC Asia Regional Contest 2018.
*	Second Prize in Vietnamese Olympiad in Informatics for Undergraduate 2018.
*	First Prize in Vietnamese Olympiad in Analysis for Undergraduate 2015.
*	Rank first in Vietnamese Olympiad in Algebra for Undergraduate 2015.
*	Second prize in Vietnamese Olympiad in Mathematics for High school Students 2014.
*	VIASM Scholar - Awarded scholarship from the Vietnam Institute for Advanced Studies in Mathematics (VIASM) for achievement in Mathematics.
*	HUST Scholar - Awarded scholarship from Hanoi University of Science and Technology (HUST) for outstanding students.

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
* Fall 2018 - Spring 2019: Teaching Assistant
  * Hanoi University of Science and Technology
  * Courses: Design and Analysis Algorithms, Discrete Mathematics

* Fall 2019 - Spring 2021: Teaching Assistant
  * University of Nebraska - Lincoln,
  * Courses: Introduction to Computer Science, Design and Analysis Algorithms
  

