# UGA Econometrics Reading Group


## Spring 2024 Schedule

{% assign current_semester = “Spring 2024” %}
<table>
<tr>
<th>
Date
</th>
<th>
Time
</th>
<th>
Location
</th>
<th>
Leader
</th>
<th>
Title
</th>
</tr>
{% for presentation in site.data.presentations %} {% if
presentation.semester == current_semester %}
<tr>
<td>
{{ presentation.date }}
</td>
<td>
{{ presentation.start-time}}–{{ presentation.end-time}}
</td>
<td>
{{ presentation.location }}
</td>
<td>
{{ presentation.leader }}
</td>
<td>
<a href="{{ presentation.link }}">{{ presentation.title }}</a>
</td>
</tr>
{% endif %} {% endfor %}
</table>
