---
layout: default
title: Class 9
nav_order: 2
currWeekNumber: 2
---
 
# {{ site.tagline }}
{: .mb-2 }
Class 9, Peking University, 2023 Fall
{: .mb-0 .fs-6 .text-grey-dk-000 }

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}
## Sources
问题解决
- 树洞
    - ICS lab有多个测评洞，例如这个整合洞：#4698353
- 搜索引擎：推荐使用**Google**，并尽快适应全英文阅读
    - 如果无法科学上网，可以使用Bing
    - CSDN / Stack Overflow
- 欢迎向助教提问！但是请先尝试自己搜索解决——这也是学习的过程之一

ICS相关资源
- CSAPP主页：http://csapp.cs.cmu.edu/
- 30分钟学会GDB：https://beej.us/guide/bggdb/
- **Vim学习: vim tutor**  http://www2.geog.ucl.ac.uk/~plewis/teaching/unix/vimtutor
    - 中英对照版：https://github.com/HanielF/VimTutor
- Linux vim git 使用视频教程: https://disk.pku.edu.cn/#/link/C1CC5B3D50AB76AC6655AFCFC0EF0E7B

其他资源
- The Missing Semester of Your CS Education: ********https://missing.csail.mit.edu/
- CS自学指南: https://csdiy.wiki/

## Schedule
{% for module in site.modules %}
{% if module.exclude != true %}
{% if module.classNumber == 9 %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endif %}
{% endif %}
{% endfor %}

<iframe src="https://www.random.org/widgets/integers/iframe.php?title=True+Random+Number+Generator&amp;buttontxt=Generate&amp;width=160&amp;height=235&amp;border=on&amp;bgcolor=%23FFFFFF&amp;txtcolor=%23777777&amp;altbgcolor=%23808080&amp;alttxtcolor=%23FFFFFF&amp;defaultmin=1&amp;defaultmax=17&amp;fixed=off" frameborder="0" width="160" height="235" style="min-height:235px;" scrolling="no" longdesc="https://www.random.org/integers/"></iframe>
<style>iframe { display: block; position: fixed; top: 60px; right: 30px;}</style>
