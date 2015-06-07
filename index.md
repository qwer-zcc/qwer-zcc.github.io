---
layout: page
title: Qwer_zcc's blog
tagline: Supporting tagline
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li>
    	<span>
    		<font size="3" >
    			{{ post.date | date_to_string }}
    		</font>
    	</span> &raquo;
    	<font size="4">
	    	<a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}
    		</a>
    	</font>
    </li>
    <article class="rexp">
    	<p><font size="2">{{ post.excerpt }}</font></p>
    </article>
  {% endfor %}
</ul>

