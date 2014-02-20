---
layout: default
title: Talk Like Kyle
subheading: All you wanted to know and more
---

<div id="home">
  <h1>Blog Posts</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>

<ul>
{\% for post in site.posts \%}
      <li><span>{\{ post.date | date_to_string }\}</span> &raquo; <a href="{\{ post.url }\}">{\{ post.title 
}\}</a></li>

{\% endfor %\}

</ul>
