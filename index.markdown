---
layout: default
title: Home
permalink: 
---

# Introduction

I was born and brought up in India. I moved to the United States for college in 2014 and ended up staying for close to 8 years. I moved back to India in June 2022.

Very few people end up moving back to India, and the ones who do usually don't document their experiences and ordeals. When I was contemplating the move, I really wished I could find real world perspectives from people who had moved back. I also found it quite difficult to gather the necessary knowledge/expertise to plan my move. The posts here are a mix of information about planning and executing the move, my experiences after moving back and my reasons for the move. I expect to add more content with time, so stay tuned!

# [Posts]({% link posts.md%})

<ul>
  {% for post in site.posts reversed%}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <!-- {{ post.excerpt }} -->
    </li>
  {% endfor %}
</ul>

