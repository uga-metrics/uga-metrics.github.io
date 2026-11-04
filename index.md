---
title: "Econometrics at UGA"
---
{% comment %}
=============================================================================
Title: Econometrics at UGA home page
Description: Current-semester seminar and reading group schedules, with calendar
  subscribe buttons and per-talk add links. The semester is set in _config.yml.
Author: Brant Callaway
Last update: 2026-11-04
Date created: 2024-02-16
=============================================================================
{% endcomment %}

<link rel="stylesheet" href="{{ '/style.css' | relative_url }}">

# Econometrics at UGA

## Seminars

The UGA Econ department will host the following econometrics seminars during the {{ site.current_semester }} semester. For {{ site.current_semester }}, seminars are held from **2:55--4:15PM** in **Orkin Hall D107**.

Economics faculty in the greater Atlanta/Athens area are welcome to attend. Often, we are able to hold one or two meeting slots with the seminar speaker for external faculty---just get in touch with the host several days before the seminar date to request a meeting slot.

### {{ site.current_semester }} Schedule

{% include calendar_subscribe.html feed="seminars.ics" name="UGA Econometrics Seminars" %}

<div class="seminar-table-wrapper">
<table class="seminar-table">
  <tr>
    <th>Date</th>
    <th>Time</th>
    <th>Location</th>
    <th>Speaker</th>
    <th>Affiliation</th>
    <th>Host</th>
    <th>Paper</th>
  </tr>
  {% for seminar in site.data.seminars %}
    {% if seminar.semester == site.current_semester %}
	<tr>
      		<td>{{ seminar.date | date: "%A, %b. %-d"}}<br>{% include calendar_links.html series="seminar" talk=seminar %}</td>
      		<td>{% if seminar['start-time'] and seminar['end-time'] %}{{ seminar['start-time'] }}--{{ seminar['end-time'] }}{% else %}TBA{% endif %}</td>
      		<td>{{ seminar.location | default: "TBA" }}</td>
      		<td>{{ seminar.speaker }}</td>
      		<td>{{ seminar.affiliation }}</td>
		<td>{{ seminar.host }}</td>
      		<td>{% include paper_link.html link=seminar.link title=seminar.title %}</td>
    	</tr>
    {% endif %}
  {% endfor %}
</table>
</div>

[[Past Seminars](past_seminars)]


## Reading Group

The Econometrics Reading Group is our internal reading group. Please see below for our current and upcoming schedules.

The organizer for this semester is [Derek Dyal](https://www.terry.uga.edu/directory/derek-dyal/). If you would like to present or be added to our mailing list, please contact Derek.


### {{ site.current_semester }} Schedule

{% include calendar_subscribe.html feed="erg.ics" name="UGA Econometrics Reading Group" %}

<table>
  <tr>
    <th>Date</th>
    <th>Time</th>
    <th>Location</th>
    <th>Leader</th>
    <th>Title</th>
  </tr>
  {% for presentation in site.data.erg %}
    {% if presentation.semester == site.current_semester %}
      <tr>
        <td>{{ presentation.date | date: "%A, %b. %-d"}}<br>{% include calendar_links.html series="erg" talk=presentation %}</td>
        <td>{% if presentation['start-time'] and presentation['end-time'] %}{{ presentation['start-time'] }}--{{ presentation['end-time'] }}{% else %}TBA{% endif %}</td>
        <td>{{ presentation.location | default: "TBA" }}</td>
        <td>{{ presentation.leader }}</td>
        <td>{% include paper_link.html link=presentation.link title=presentation.title %}</td>
      </tr>
    {% endif %}
  {% endfor %}
</table>

[[Past ERG Meetings](past_erg)]
