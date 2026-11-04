{% comment %}
=============================================================================
Title: Past seminars
Description: Seminar schedules from earlier semesters.
Author: Brant Callaway
Last update: 2026-11-04
Date created: 2024-09-12
=============================================================================
{% endcomment %}

## Past Seminars

### Spring 2026 Schedule

{% assign current_semester = "Spring 2026" %}
<table>
  <tr>
    <th>Date</th>
    <th>Speaker</th>
    <th>Affiliation</th>
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
      		<td>{% include paper_link.html link=seminar.link title=seminar.title %}</td>
    	</tr>
    {% endif %}
  {% endfor %}
</table>

### Fall 2025 Schedule

{% assign current_semester = "Fall 2025" %}
<table>
  <tr>
    <th>Date</th>
    <th>Speaker</th>
    <th>Affiliation</th>
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
      		<td>{% include paper_link.html link=seminar.link title=seminar.title %}</td>
    	</tr>
    {% endif %}
  {% endfor %}
</table>

### Spring 2025 Schedule

{% assign current_semester = "Spring 2025" %}
<table>
  <tr>
    <th>Date</th>
    <th>Speaker</th>
    <th>Affiliation</th>
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
      		<td>{% include paper_link.html link=seminar.link title=seminar.title %}</td>
    	</tr>
    {% endif %}
  {% endfor %}
</table>

### Spring 2024 Schedule

{% assign current_semester = "Spring 2024" %}
<table>
  <tr>
    <th>Date</th>
    <th>Speaker</th>
    <th>Affiliation</th>
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
      		<td>{% include paper_link.html link=seminar.link title=seminar.title %}</td>
    	</tr>
    {% endif %}
  {% endfor %}
</table>
