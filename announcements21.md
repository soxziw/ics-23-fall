---
layout: default
title: Announcements
nav_exclude: true
description: A feed containing all of the class announcements.
---

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{% if announcement.class == 21 | announcement.class == 0 %}
{{ announcement }}
{% endif %}
{% endfor %}
