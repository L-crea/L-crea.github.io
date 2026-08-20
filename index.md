---
layout: default
title: L-crea's Blog
---

# L-crea's Blog

你好，这里是我的技术博客。

我会在这里记录自己学习计算机科学与技术的过程。

## 最近文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
