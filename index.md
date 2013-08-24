---
layout: page
title: Hello World!
---
{% include JB/setup %}
## 欢迎来到星光灿烂的博客
#### 博客列表
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: "%Y %m %d" }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

