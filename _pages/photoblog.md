---
layout: page
permalink: /photoblog/
title: Photo Blog
---

<div id="archives">
  <section id="archive">
	{%for post in site.posts %}
	  
	  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
	  {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
       
	  {% if year != nyear %}
	  	<h3 style="text-align:left;">{{ post.date | date: '%Y' }}</h3>
	  {% endif %}
	
	{% if post.categories contains 'Photoblog' %}

	  <p><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      
	{% endif %}
    
	{% endfor %}
  </section>
</div>
