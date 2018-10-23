---
layout: page
---

Follow Lund University in the training before, and at [NWERC 2018](http://www.nwerc.eu/), the north western european qualification for the World Championships in competitive programming in teams - ICPC.

## Blog
<ul class="posts">
    {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
