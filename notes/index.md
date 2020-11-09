---
title: About these notes
---
{% for notes in collections.notes %}
    <h2><a href="{{ notes.url | url }}">{{ notes.data.pageTitle }}</a></h2>
    <em>{{ notes.date | date: "%Y-%m-%d" }}</em>
	{% endfor %}
