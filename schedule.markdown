---
layout: page
title: Schedule
permalink: /schedule/
---


<link href="https://kbrl.github.io/img/general.css" rel="stylesheet"></link>

<table class="demo">
	<caption></caption>
	<thead>
	<tr>
		<th>Time<br>(JST, GMT+09:00)</th>
		<th>Category</th>
		<th>Title & Speaker(s)</th>
	</tr>
	</thead>
	<tbody>
	<tr>
		<td>&nbsp;08:45</td>
		<td>&nbsp;Opening Remarks</td>
		<td>&nbsp;[KBRL Organizers](https://kbrl.github.io/organizers/)</td>
	</tr>
	<tr>
		<td>&nbsp;</td>
		<td>&nbsp;</td>
		<td>&nbsp;<a href="https://kbrl.github.io/organizers/">KBRL Organizers</a></td>
	</tr>
	<tr>
		<td>&nbsp;</td>
		<td>&nbsp;</td>
		<td>&nbsp;</td>
	</tr>
	<tr>
		<td>&nbsp;</td>
		<td>&nbsp;</td>
		<td>&nbsp;</td>
	</tr>
	</tbody>
</table>



Tentative, to be announced.

<div class="container">
  <div class="row">
    <table class="table">
        {% for s in site.data.schedule %}
        <tr>
        <td>{{ s[1].start }}</td>
        {% if s[1].type == "General" %}
          <td>{{ s[1].event }}</td>
          <td></td>
        {% elsif s[1].type == "Invited" %}
          <td class="success"><b>Invited Talk</b></td>
          {% assign speaker_id = s[1].event %}
          {% assign speaker = site.data.speakers[speaker_id] %}
          <td class="success">
          <a href="{{speaker.url}}">{{ speaker.name }}</a>, {{speaker.affiliation}}
          {% if speaker.title == "TBA" %}
          {% else %}
          <br><i><b>{{ speaker.title }}</b></i>
          {% endif %}
          </td>
        {% elsif s[1].type == "Contributed" %}
          <td><i>Contributed Talk</i></td>
          {% assign paper_id = s[1].event %}
          {% assign paper = site.data.papers[paper_id] %}
          <td>
            {{ paper.authors }}<br>
            {% if paper_id == "paper_52" %}
              <span class="bg-danger">Best Paper:</span> 
            {% endif %}
            {% if paper_id == "paper_4" %}
              <span class="bg-danger">Best Paper:</span> 
            {% endif %}
            <i>{{ paper.title }}</i>
            {% if paper.alt_url == "" %}
              (<a href="{{ site.baseurl }}/papers/KR2ML_2019_{{ paper_id }}.pdf">PDF</a>)
            {% elsif paper.alt_url == "NONE" %}
            {% else %}
              (<a href="{{ paper.alt_url }}">PDF</a>)
            {% endif %}
          </td>
        {% elsif s[1].type == "Spotlights" %}
          <td>Spotlights</td>
          <td><a href="#{{s[0]}}">{{ s[1].event }}</a></td>
        {% elsif s[1].type == "Break" %}
          <td class="info"></td>
          <td class="info">{{ s[1].event }}</td>
        {% endif %}

        <!-- <td>
            {% capture id %}{{ p[0] }}{% endcapture %}
            {{ s }}
        </td> -->
        </tr>
        {% endfor %}
    </table>
  </div>
