---
layout: page
title: Archive
permalink: /archive/
---


<div class="archive">

  <ul class="post-list">
    {% for post in site.posts %}
	  {% assign currentdate = post.date | date: "%Y" %}
	  {% if currentdate != date %}
	    {% unless forloop.first %}</ul>{% endunless %}
	    <h1 id="y{{post.date | date: "%Y"}}">{{ currentdate }}</h1>
	    <ul>
	    {% assign date = currentdate %}
	  {% endif %}
	    <li><a href="{{ post.url }}"><span class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</span> - {{ post.title }}</a></li>
	  {% if forloop.last %}</ul>{% endif %}
	{% endfor %}
  </ul>

</div>
 

