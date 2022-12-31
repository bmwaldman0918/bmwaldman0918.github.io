---
layout: page
title: Resume
permalink: /resume/
order: 2
---
<h2>Education</h2>
<b>The University of Chicago</b>
<br>
<i>B.S. in Computer Science, expected June 2025</i>
<br>
GPA: 3.7/4
<br>
Selected Coursework: 
<ul>
	<li> <a href="https://people.cs.uchicago.edu/~timng/151/a21/"> Introduction to Computer Science I </a> (A-)</li>
	<li> <a href="http://collegecatalog.uchicago.edu/thecollege/computerscience/#courseinventory"> Honors Introduction to Computer Science II </a> (A)</li>
	<li> <a href="https://sites.google.com/site/cs154uchicago/main/logisticsfaqs"> Introduction to Computer Systems </a> (A)</li>
	<li> <a href="http://cmsc-27100.cs.uchicago.edu/2018-winter/"> Discrete Math</a> (A-)</li>
	<li> <a href="https://www.cs.umd.edu/class/fall2020/cmsc131-010X-030X/"> Object-Oriented Programming I</a>* (A+)</li>
	<li> <a href="https://www.cs.umd.edu/class/spring2021/cmsc132-01XX/"> Object-Oriented Programming II</a>* (A)</li>
	
</ul>
<i>*Taken at the University of Maryland</i>

<i>**There is no publicly available webpage for this course but it is based on these notes</i>

<h2>Experience</h2>
{% assign sorted_jobs = site.jobs | sort:"order" %}
{% for job in sorted_jobs %}
  <p><a href="{{ job.url }}"><b>{{ job.jobtitle }}</b></a>,
  {% if job.link %}
  	<a href="{{ job.link }}"><i>{{ job.title }}</i></a>, {{ job.time }}
  {% else %}
  <i>{{ job.title }}</i>, {{ job.time }}
  {% endif %}
  </p>
{% endfor %}
<h2>Skills</h2>
<b>Proficient in:</b> Java, Python, C, Git, GitHub, SVN, HTML, CSS, Jekyll, VS Code, Eclipse, JetBrains IDEs
<h2>Awards</h2>
<ul>
	<li><a href="https://www.nationalmerit.org/s/1758/interior.aspx?sid=1758&gid=2&pgid=424">National Merit Scholar</a>, 2021</li>
	<li><a href="https://apstudents.collegeboard.org/awards-recognitions/ap-scholar-award">AP Scholar with Distinction</a>, 2020</li>
	<li><a href="https://coolidgescholars.org/senators/">Coolidge Senator</a>, 2020</li>
	<li>Tournament of Champions Qualifier, Lincoln-Douglas Debate, 2019, 2020, 2021</li>
	<li> <a href="https://www.tabroom.com/index/tourn/postings/entry_record.mhtml?tourn_id=16776&entry_id=3272280">Semifinalist</a>, Harvard Forensics Tournament, Lincoln-Douglas Debate, 2021</li>
</ul>
