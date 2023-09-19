---
layout: default
title: Calendar
nav_order: 5
description: The weekly event schedule.
---

# Weekly Calendar

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}