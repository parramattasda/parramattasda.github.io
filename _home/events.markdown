---
title: Events
date: 2016-06-24 11:26:00 +10:00
position: 1
---

<i class="fa fa-calendar-o fa-5x"></i>

<ul class="list-unstyled">
{% for item in site.events limit:3 %}
  <li><strong>{{ item.title }}</strong> {{ item.event_date | date: '%B %d, %Y' }}</li>
{% endfor %}
</ul>
