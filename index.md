---
layout: page
title: Software Gardener
tagline: Do it right. And do the right things.
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <div class="page-header"><h1><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h1></div>
    {{post.content}}
  {% endfor %}
</ul>
