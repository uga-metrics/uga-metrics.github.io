---
title: "Econometrics at UGA"
---

# Econometrics at UGA

## Seminars

The UGA Econ department will host the following econometrics seminars during the Fall 2025 semester. For Fall 2025, seminars are held from 4:00--5:15 in Correll Hall 313.

Economics faculty in the greater Atlanta/Athens area are welcome to attend. Often, we are able to hold one or two meeting slots with the seminar speaker for external faculty---just get in touch with the host several days before the seminar date to request a meeting slot.

### Fall 2025 Schedule

{% assign current_semester = "Fall 2025" %}
<table>
  <tr>
    <th>Date</th>
    <th>Speaker</th>
    <th>Affiliaton</th>
    <th>Host</th>
    <th>Paper</th>
  </tr>
  {% for seminar in site.data.seminars %}
    {% if seminar.semester == current_semester %}
	<tr>
      		<td>{{ seminar.date | date: "%A, %b. %-d"}}</td>
      		<td>{{ seminar.speaker }}</td>
      		<td>{{ seminar.affiliation }}</td>
		<td>{{ seminar.host }}</td>
      		<td><a href="{{ seminar.link }}">{{ seminar.title }}</a></td>
    	</tr>
    {% endif %}
  {% endfor %}
</table>

[[Past Seminars](past_seminars)]


## Reading Group

The Econometrics Reading Group is our internal reading group. Please see below for our current and upcoming schedules.

The organizer for this semester is [Derek Dyal](https://www.terry.uga.edu/directory/derek-dyal/). If you would like to present or be added to our mailing list, please contact Derek.


### Fall 2025 Schedule

{% assign current_semester = "Fall 2025" %}
<table>
  <tr>
    <th>Date</th>
    <th>Time</th>
    <th>Location</th>
    <th>Leader</th>
    <th>Title</th>
  </tr>
  {% for presentation in site.data.erg %}
    {% if presentation.semester == current_semester %}
      <tr>
        <td>{{ presentation.date | date: "%A, %b. %-d"}}</td>
        <td>{{ presentation['start-time']}}--{{ presentation['end-time']}}</td>
        <td>{{ presentation.location }}</td>
        <td>{{ presentation.leader }}</td>
        <td><a href="{{ presentation.link }}">{{ presentation.title }}</a></td>
      </tr>
    {% endif %}
  {% endfor %}
</table>

[[Past ERG Meetings](past_erg)]
