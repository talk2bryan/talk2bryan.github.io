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
* M.Sc. in Computer Science, University of Manitoba, 2022
  * Published a thesis on the use of a hybrid database (MySQL and Graph) in supporting transportation data analytics

* B.Sc. in Computer Science (Major Co-Op), University of Manitoba, 2018
  * Computer Science concentrations in Software Engineering and Databases
  * Minors in Economics and Statistics

Work experience (not up-to-date, check LinkedIn)
======
* Fall 2018: Teaching Assistant
  * Dept. of Computer Science, University of Manitoba
    * Conducting class tutorials, debugging students’ code, and evaluating submissions.

* Summer 2018: Software Engineer Co-Op (Co-op Work Term III)
  * Electronic Arts
    * Maintained and created tools for the content delivery pipeline.
    * Validated Live content data, as well as system failures from a prioritized backlog.

* Fall 2014 - Winter 2018: Teaching Assistant
  * Dept. of Computer Science, University of Manitoba
    * Courses are listed in detail in the Teaching Assistant Roles tab.

* Summer 2017: Research Assistant (Co-op Work Term II)
  * Database & Data Mining Laboratory, University of Manitoba
    * Created an orientation-free frequent pattern visualizer for Big Data, using D3.js. The goal was to enhance collaboration among users which, from my research on other visualization tools, was a common limitation.
    * Supervisor: [Dr. Carson K. Leung](http://www.cs.umanitoba.ca/~kleung/ "Dr. Carson K. Leung's Homepage")

* Winter 2017: Software Engineering Intern (Co-op Work Term I)
  * Google Inc.
    * Created a dashboard to view/query usage, demand, and supply of resources (cpu, disk, millicpu, milligpu) across clusters in different regions. 
    * Facilitated content migration by providing an export feature of said data to spreadsheets.
  
Skills
======
* Programming Languages
  * Python, Java, C/C++, Haxe, HTML/CSS, Javascript, SQL, R, Ruby
* Frameworks
  * Poetry, FastAPI, Spring, Rails, CUDA, ROBOTIS
* Databases
  * MySQL, SQL Server, Amazon Neptune
* DevOps
  * GitHub Actions, Bitbucket Pipes, Nginx, Docker, Vagrant, Capistrano, TravisCI
* Operating Systems
  * \*nix, Windows
* Version Control
  * Git, Perforce
* Miscellenous
  * Jira, JProfiler, OpenCV, gdb, pdb, clang

Publications
======
{% if site.author.googlescholar %}
  * You can find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching Roles
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
