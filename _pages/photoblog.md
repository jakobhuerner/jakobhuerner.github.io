---
layout: page
permalink: /photoblog/
title: Photo Blog
---

<div id="archives">
  <section id="archive">
      {%for post in site.posts %}
	  {% if post.categories contains 'Photoblog' %}

      {% capture month %}{{ post.date | date: '%B %Y' }}{% endcapture %}
      {% capture nmonth %}{{ post.next.date | date: '%B %Y' }}{% endcapture %}
      {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
      {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
         
      {% if month != nmonth %}
      <h3 style="text-align:left;">{{ post.date | date: '%B %Y' }}</h3>
      {% endif %}
      <p><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      {% endif %}
	  {% endfor %}
  </section>
</div>
