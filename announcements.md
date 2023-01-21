---
layout: page
title: Announcements
nav_exclude: true
description: A feed containing all class announcements.
---

# Announcements

<!--
## Table of contents - not able to stably link to the anchor due to the fact that the subdirectory appears as part of the tag
{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
 [{{ announcement.title }}](#{{ announcement.url }})
{% endfor %}
-->

---


{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
