---
layout: page
permalink: /personal/
title: Personal
---

# Hallo Welt

Das ist ein Text.

## Das ist eine Unterüberschrift

Unten kommen die Beiträge.

# Väterblog

<div id="archives">
  <section id="archive">
      {%for post in site.posts %}
	  {% if post.categories contains 'Vaeterblog' %}
      <p><b><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a></b> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      {% endif %}
	  {% endfor %}
      </ul>
  </section>
</div>