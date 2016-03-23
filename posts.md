---
layout: page
title: Posts
permalink: /posts/
feature-img: "img/sample_feature_img_3.png"
---
<ul style="list-style-type:none">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>