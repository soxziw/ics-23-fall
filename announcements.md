---
layout: default
title: Announcements
nav_exclude: true
description: A feed containing all of the class announcements.
---

# Announcements

{% assign announcements = site.announcements.test | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
