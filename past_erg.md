## Past ERG Meetings

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

### Spring 2025 Schedule

{% assign current_semester = "Spring 2025" %}
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

### Fall 2024 Schedule

{% assign current_semester = "Fall 2024" %}
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

### Summer 2024 Schedule

{% assign current_semester = "Summer 2024" %}
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

### Fall 2023 Schedule

{% assign current_semester = "Fall 2023" %}
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

### Spring 2023 Schedule

{% assign current_semester = "Spring 2023" %}
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



### Fall 2022 Schedule

{% assign current_semester = "Fall 2022" %}
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

