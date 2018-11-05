---
layout: page
---

Follow [`from __future__ import solution`](/from_future) and [`¡i¡i¡`](/iiiii) representing [Lund University](https://www.lu.se/) at [NWERC 2018](http://www.nwerc.eu/), the north western european qualification for the World Championships in competitive programming in teams - ICPC.

## Blog
<ul class="posts">
    {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
