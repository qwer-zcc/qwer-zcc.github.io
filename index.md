---
layout: page
title: Qwer_zcc's blog
tagline: Supporting tagline
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span><font size="5" >{{ post.date | date_to_string }}</font></span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    <article class="rexp">
    	<p>{{ post.excerpt }} </p>
    </article>
  {% endfor %}
</ul>

