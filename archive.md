---
layout: page
title: Archive
---

<ul class="post-list">
{% for post in site.posts %}
  <li>
  	<span class="post-meta">{{ post.date | date_to_string }}</span> 
  	<h2>
  		<a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
  	</h2>
  </li>
{% endfor %}
</ul>