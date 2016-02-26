---
layout: page
title: Hannah's Github Portfolio
tagline: Assorted coding projects
---
{% include JB/setup %}

Welcome to a few pieces of my coding journey. As I experiment and create more, this site will contain more projects. In the meantime, you're welcome to check out my [LinkedIn profile](    Public Profile
        https://www.linkedin.com/in/hannahnotess) to learn more about me and my work.


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
