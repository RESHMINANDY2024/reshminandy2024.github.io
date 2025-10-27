---
layout: </head><body class="container">
title: All posts
permalink: /posts/
---
<h1>All posts</h1>
<ul class="posts">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="muted"> · {{ post.date | date: "%b %d, %Y" }} · {{ post.content | number_of_words | divided_by:200 | ceil }} min read</span>
  </li>
{% endfor %}
</ul>
