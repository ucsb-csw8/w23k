---
layout: page
title: Calendar
nav_order: 3
description: Listing of course topics and due dates.
---

# Course Calendar (Topics and due dates)

See the [Schedule and Roadmap]({{site.url}}/{{site.baseurl}}/success/#time-management-and-scheduling) suggestions. 

In our course, each week covers roughly 1 chapter from zyBooks, so "Week 1" in zyBooks is effectively Chapter 1 and so on.

We have the following course activities that need to be completed in zyBooks on a weekly basis: 
* **PA**{: .label .label-orange }(Participation Activities), 
* **CA**{: .label .label-blue }(Challenge Activities), 
* **LA**{: .label .label-green }(Lab Activities).

To make sure that you get started with the labs, we have **LA Checkpoints**{: .label .label-green }, which you will need to submit right after the labs.
See more information in the [respective FAQ explanation]({{site.url}}/{{site.baseurl}}/faq#what-is-the-lab-checkpoint-score-in-gradebook).

Additionally, at the end of each week, you are asked to reflect on your learning journey that week and submit a **Reflection** linked on Gauchospace.
<!--In order to ensure that you are rewarded for participating during the synchronous times, we will be collecting your progress on the breakout room activities and participation in the in-class activities.-->

All due times in our class are at **11:59PM Pacific time **.


<!--[Jump to the current week]({{ site.url }}{{ site.baseurl }}/calendar#week-1){: .btn .btn-blue }-->
{% for module in site.modules %}
{{ module }}
{% endfor %}
