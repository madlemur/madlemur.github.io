---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Home
layout: default
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a> <span style="font-size: medium;">{{ post.date }}</span></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>