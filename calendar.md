---
layout: default
title: Calendar
nav_order: 6
description: The weekly event schedule.
---
# Semester Calender

| Week | Lecture Number | Date    | Lecture                          | TA Session          | Lab               |
| ---- | -------------- | ------- | -------------------------------- | ------------------- | ----------------- |
| 1    | #1             | Sept 11 | Overview                         |                     |                   |
|      | #2             | Sept 13 | Bits and Bytes/Integers          | Lecture #1          |                   |
| 2    | #3             | Sept 18 | Floating Point                   |                     | L1 (datalab) delay  |
|      | #4             | Sept 20 | Machine Prowg: Basics            | Lecture #2/3        |                   |
| 3    | #5             | Sept 25 | Machine Prog: Control            |                     |                   |
|      | #6             | Sept 27 | Machine Prog: Procedures         | Lecture #4/5        | L2 (bomblab) out  |
| 4    |                | Oct 2   | No Lecture: National Day Holiday |                     |                   |
|      |                | Oct 4   | No Lecture: National Day Holiday |                     |                   |
| 5    | #7             | Oct 9   | Machine Prog: Data               |                     |                   |
|      | #8             | Oct 11  | Machine Prog: Advanced           | Lecture #6/7        | L3(attacklab) out |
| 6    | #9             | Oct 16  | Processor Arch: ISA&Logic        |                     |                   |
|      | #10            | Oct 18  | Processor Arch: Sequential       | Lecture #8/9        | L4 (archlab) out  |
| 7    | #11            | Oct 23  | Processor Arch: Pipelined        |                     |                   |
|      | #12            | Oct 25  | The Memory Hierarchy             | Lecture #10/11      |                   |
| 8    | #13            | Oct 30  | Cache Memories                   |                     | L5 (cachelab) out |
|      | #14            | Nov 1   | Program optimization             | Lecture #12/13/14   |                   |
| 9    | #15            | Nov 6   | Midterm                          |                     |                   |
|      | #16            | Nov 8   | Seminar                          | Comments on Midterm |                   |
| 10   | #17            | Nov 13  | Linking I                        |                     |                   |
|      | #18            | Nov 15  | Linking II                       | Lecture #17         |                   |
| 11   | #19            | Nov 20  | ECF: Exceptions & Processes      |                     |                   |
|      | #20            | Nov 22  | ECF: Signals & Nonlocal Jumps    | Lecture #18/19      | L6 (tshlab) out   |
| 12   | #21            | Nov 27  | System Level I/O                 |                     |                   |
|      | #22            | Nov 29  | Virtual Memory: Concepts         | Lecture #20/21      |                   |
| 13   | #23            | Dec 4   | Virtual Memory: Systems          |                     | L7(malloclab) out |
|      | #24            | Dec 6   | Dynamic Memory Allocation        | Lecture #22/23      |                   |
| 14   | #25            | Dec 11  | Network Programming I            |                     |                   |
|      | #26            | Dec 13  | Network Programming II           | Lecture #24/25      | L8 (proxylab) out |
| 15   | #27            | Dec 18  | Concurrent Programming           |                     |                   |
|      | #28            | Dec 20  | Synchronization: Basics          | Lecture #26/27/28   |                   |
| 16   | #29            | Dec 25  | Synchronization: Advanced        |                     |                   |
|      | #30            | Dec 27  | Final Review                     | Final Review        |                   |

# Weekly Calendar

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}