---
layout: single
title:  "Home"
date:   2023-10-16 13:30:00 -0500
permalink: /
author_profile: true
---

until i post something. this will live here.

#### Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>