---
layout: page
title: Resume
permalink: /resume/
order: 2
---
<h2>Education</h2>
<b>The University of Chicago</b>
<br>
<i>Bachelors of Arts, expected June 2025</i>
<br>
GPA: 3.6/4
<br>
Selected Coursework: 
<ul>
	<li> <a href="https://people.cs.uchicago.edu/~timng/151/a21/"> Introduction to Computer Science I </a> </li>
	<li> <a href="https://www.cs.umd.edu/class/fall2020/cmsc131-010X-030X/"> Object-Oriented Programming I</a>*</li>
	<li> <a href="https://www.cs.umd.edu/class/spring2021/cmsc132-01XX/"> Object-Oriented Programming II</a>*</li>
</ul>
<i>*Taken at the University of Maryland through high school dual enrollment program</i>

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
<p>&#9989; Java, Python, Racket, Eclipse</p>
<p>&#128076; HTML/CSS, SQL, C, Jekyll, Git, French, Adobe Photoshop/Illustrator</p>
<p>&#129295; JavaScript, PHP</p>
<h2>Awards</h2>
<ul>
	<li><a href="https://www.nationalmerit.org/s/1758/interior.aspx?sid=1758&gid=2&pgid=424">National Merit Scholar</a>, 2021</li>
	<li><a href="https://apstudents.collegeboard.org/awards-recognitions/ap-scholar-award">AP Scholar with Distinction</a>, 2020</li>
	<li><a href="https://coolidgescholars.org/senators/">Coolidge Senator</a>, 2020</li>
	<li>Tournament of Champions Qualifier, Lincoln-Douglas Debate, 2019, 2020, 2021</li>
	<li> <a href="https://www.tabroom.com/index/tourn/postings/entry_record.mhtml?tourn_id=16776&entry_id=3272280">Semifinalist</a>, Harvard Forensics Tournament, Lincoln-Douglas Debate, 2021</li>
</ul>
