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
GPA: 3.8/4
<br>
Selected Coursework: 
<ul>
	<li> Introduction to Cryptography (A) </li>
	<li> Introduction to Formal Languages (A) </li>
	<li> Type Theory (A) </li>
	<li> Programming Languages (A-) </li>
	<li> <a href="https://classes.cs.uchicago.edu/archive/2024/winter/23200-1/"> Introduction to Computer Seucity </a> (B+)</li>
	<li> Introduction to Database Systems (B+)</li>
</ul>

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
<b>Proficient in:</b> Java, Python, C, Git, GitHub, SVN, HTML, CSS, Jekyll, Rust
<h2>Awards</h2>
<ul>
	<li><a href="https://www.nationalmerit.org/s/1758/interior.aspx?sid=1758&gid=2&pgid=424">National Merit Scholar</a>, 2021</li>
	<li><a href="https://apstudents.collegeboard.org/awards-recognitions/ap-scholar-award">AP Scholar with Distinction</a>, 2020</li>
	<li><a href="https://coolidgescholars.org/senators/">Coolidge Senator</a>, 2020</li>
	<li>Tournament of Champions Qualifier, Lincoln-Douglas Debate, 2019, 2020, 2021</li>
	<li> <a href="https://www.tabroom.com/index/tourn/postings/entry_record.mhtml?tourn_id=16776&entry_id=3272280">Semifinalist</a>, Harvard Forensics Tournament, Lincoln-Douglas Debate, 2021</li>
</ul>
