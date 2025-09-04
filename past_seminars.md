## Past Seminars

### Spring 2025 Schedule

{% assign current_semester = "Spring 2025" %}
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
