---
layout: page
---

Follow [`from __future__ import solution`]({{site.baseurl}}/from_future) and [`¡i¡i¡`]({{site.baseurl}}/iiiii) representing [Lund University](https://www.lu.se/) at [NWERC 2018](http://www.nwerc.eu/), the north western european qualification for the World Championships in competitive programming in teams - ICPC.

The contest starts at 10:00 the 25th of November and lasts for 5 hours. 

The live score board of the competition will be available at [nwerc.eu/scoreboard/public/](http://www.nwerc.eu/scoreboard/public/).

The problems will be possible to find 30 minutes after contest start at the open contest at [open.kattis.com/contests/nwerc18open](https://open.kattis.com/contests/nwerc18open). 

## Blog
<ul class="posts">
    {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
