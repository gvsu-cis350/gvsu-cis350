---
layout: page
title: Instructor
description: A listing of all the course staff members.
---

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

