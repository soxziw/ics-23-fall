---
layout: default
title: Schedule
nav_order: 1
currWeekNumber: 2
---
 
# {{ site.tagline }}
{: .mb-2 }
Class 6, Peking University, 2023 Fall
{: .mb-0 .fs-6 .text-grey-dk-000 }

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Schedule
{% for module in site.modules %}
{% if module.exclude != true %}
{% if module.classNumber == "6" %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endif %}
{% endif %}
{% endfor %}

<iframe src="https://www.random.org/widgets/integers/iframe.php?title=True+Random+Number+Generator&amp;buttontxt=Generate&amp;width=160&amp;height=235&amp;border=on&amp;bgcolor=%23FFFFFF&amp;txtcolor=%23777777&amp;altbgcolor=%23808080&amp;alttxtcolor=%23FFFFFF&amp;defaultmin=1&amp;defaultmax=17&amp;fixed=off" frameborder="0" width="160" height="235" style="min-height:235px;" scrolling="no" longdesc="https://www.random.org/integers/"></iframe>
<style>iframe { display: block; position: fixed; top: 60px; right: 30px;}</style>
