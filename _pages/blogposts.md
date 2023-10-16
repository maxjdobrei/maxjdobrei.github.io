---
layout: single
title:  "Posts"
date:   2023-10-16 13:30:00 -0500
permalink: /blogposts/
author_profile: true
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>