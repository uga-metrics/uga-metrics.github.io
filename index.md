---
title: "Econometrics at UGA"
---

## Seminars

The UGA Econ department will host the following econometrics seminars during the Spring 2024 semester.  For Spring 2024, seminars are held from 4:00--5:15 in Orkin Hall D107.

Economics faculty in the greater Atlanta/Athens area are welcome to attend.  Often, we are able to hold one or two meeting slots with the seminar speaker for external faculty---just get in touch with the host several days before the seminar date to request a meeting slot.

### Spring 2024 Schedule

{% assign current_semester = "Spring 2024" %}
<table>
  <tr>
    <th>Date</th>
    <th>Speaker</th>
    <th>Affiliaton</th>
	<th>Host</th>
    <th>Paper</th>
  </tr>
  {% for seminar in site.data.seminars %}
    <tr>
      <td>{{ seminar.date | date: "%A, %b. %-d"}}</td>
      <td>{{ seminar.speaker }}</td>
      <td>{{ seminar.affiliation }}</td>
	   <td>{{ seminar.host }}</td>
      <td><a href="{{ seminar.link }}">{{ seminar.title }}</a></td>
    </tr>
  {% endfor %}
</table>

## Reading Group

The Econometrics Reading Group is our internal reading group.  Please see below for our Spring 2024 schedule.

The organizer for this semester is [Hugo Sant'Anna](https://hsantanna.org/).  If you would like to present or be added to our mailing list, please contact Hugo.

### Spring 2024 Schedule

{% assign current_semester = "Spring 2024" %}
<table>
  <tr>
    <th>Date</th>
    <th>Time</th>
    <th>Location</th>
    <th>Leader</th>
    <th>Title</th>
  </tr>
  {% for presentation in site.data.erg %}
    <tr>
      <td>{{ presentation.date | date: "%A, %b. %-d"}}</td>
      <td>{{ presentation['start-time']}}--{{ presentation['end-time']}}</td>
      <td>{{ presentation.location }}</td>
      <td>{{ presentation.leader }}</td>
      <td><a href="{{ presentation.link }}">{{ presentation.title }}</a></td>
    </tr>
  {% endfor %}
</table>
