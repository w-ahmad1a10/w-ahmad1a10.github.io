---
layout: page
title: Waleed Ahmad 
permalink: /blog/
---

Here's a list of all my blog posts:

<ul>
  {% for post in site.posts %}
    <li style="margin-bottom: 12px;">
      <a href="{{ post.url }}" style="font-size: 18px; font-weight: 500;">
        {{ post.title }}
      </a>
      <br>
      <span style="color: #666; font-size: 14px;">
        {{ post.date | date: "%B %d, %Y" }}
      </span>
    </li>
  {% endfor %}
</ul>
