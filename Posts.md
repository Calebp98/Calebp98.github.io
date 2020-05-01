---
layout: default
title: Posts
---
<head>
  <script src="/assets/js/p5.js"></script>
  <script src="/assets/js/posts.js"></script>
  <script src="/assets/js/p5.play.js"></script>
</head>

<div id="anime2" markdown="1"></div>


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
