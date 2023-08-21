---
layout: home
title: Home
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: COMP 1336
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

## About the Class

COMP 1336 is an introductory class designed for students with no formal exposure to computer science or programming. The goal is to provide a gentle but thorough introduction to computer science that will prepare students to either take further computer science courses, or use computer science in their field of study.

See the [Syllabus page](syllabus.md) for more details on course policies.

## Course Materials
{% for module in site.modules %} {{ module }} {% endfor %}