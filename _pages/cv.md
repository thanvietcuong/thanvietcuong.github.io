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

Research Interests
======
Graph algorithms, computational geometry, discrete metric spaces, and theoretical computer science.

Education
======
* Ph.D. in Computer Science, University of Massachusetts Amherst, 2021 - 2027 (expected June 2027)
  * Advisor: [Dr. Hung Le](https://hunglvosu.github.io)
* M.S. in Computer Science, University of Nebraska - Lincoln, 2019 - 2021
* B.S. in Computer Science, Hanoi University of Science and Technology, 2014 - 2019
  * Highest GPA in the Honors Program

Honors and Awards
======
* Google PhD Fellowship in Algorithms and Optimization, 2025 - 2027
  * One of three recipients in Algorithms and Optimization; provides two years of research support.
* 1st Place, ICPC North Central North America Regional Contest, 2019
* 2nd Prize, ICPC Asia Regional Contest, 2018
* 2nd Prize, Vietnamese Olympiad in Informatics for Undergraduates, 2018
* 1st Prize, Vietnamese Olympiad in Analysis for Undergraduates, 2015
* 1st Prize, Vietnamese Olympiad in Linear Algebra for Undergraduates, 2015

Publications
======
See the [Publications](/publications/) page for the full list with links.

  <ul>{% assign cv_pubs = site.publications | sort: "date" | reverse %}{% for post in cv_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% assign cv_talks = site.talks | sort: "date" | reverse %}{% for post in cv_talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Research Experience
======
* Dec 2024 - Mar 2025: Student Researcher, Google Research
  * Developed routing algorithms for temporal graphs with the Google Geo team.
* Aug - Oct 2023: Student Researcher, Google Research
  * Worked with the Graph Mining team in the Algorithms and Optimization group.
  * Implemented and improved graph-based sampling and distillation algorithms for Gemini.
* 2021 - present: Research Assistant, University of Massachusetts Amherst
  * Conduct research in graph algorithms and computational geometry, with emphasis on spanners, tree covers, and metric algorithms.
* Aug 2022: Visiting Researcher, Tel Aviv University, Israel
  * Research visit supported by the NSF-BSF grant "Towards a Unified Theory of Spanners."
  * Conducted research on distributed and fault-tolerant graph algorithms with [Shay Solomon](https://sites.google.com/site/soloshay/home).

Mentoring and Professional Service
======
* Research Mentor, [Early Research Scholars Program (ERSP)](https://sites.google.com/umass.edu/ersp-cics), UMass Amherst. Mentored undergraduate students from underrepresented groups in research projects in theoretical computer science.
* Reviewer: *Discrete & Computational Geometry*; *SIAM Journal on Discrete Mathematics*; *ACM Journal of Experimental Algorithmics*; STOC 2025 - 2026; SODA 2022, 2024 - 2026; FOCS 2024; SoCG 2026; ESA 2026; APPROX 2026; WADS 2019.

Teaching
======
* Fall 2019 - Spring 2021: Teaching Assistant, University of Nebraska - Lincoln
  * Courses: Introduction to Computer Science, Design and Analysis of Algorithms
* Fall 2018 - Spring 2019: Teaching Assistant, Hanoi University of Science and Technology
  * Courses: Design and Analysis of Algorithms, Discrete Mathematics

Technical Skills
======
* Programming: C++, Python, Java; prior experience with C# and OCaml.
* Systems: Familiar with large-scale distributed systems and production research infrastructure.
