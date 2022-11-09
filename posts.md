---
layout: default
title: Posts
permalink: /posts
--- 

# Posts

<ul>
  {% for post in site.posts reversed%}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <!-- {{ post.excerpt }} -->
    </li>
  {% endfor %}
</ul>