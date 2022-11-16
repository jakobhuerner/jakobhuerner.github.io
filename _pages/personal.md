---
layout: page
permalink: /personal/
title: Personal
---

_This section is written in German._

Der Fokus dieses Bereichs liegt auf Themen, die in meinem besonderen Interesse liegen: Familie und Elternsein, Gesellschaft, Nachhaltigkeit etc.

Der Bereich ist in Deutsch gehalten. Die Themen sind oft direkt mit dem Umfeld in Österreich verbunden, weshalb sie im Wesentlichen nur für deutschprachige Leserinnen und Leser von Interesse sein werden.

Die Beiträge geben meine persönlichen Erfahrungen und Meinungen wieder.

## Väterblog

Für mich als Vater und gesellschaftlich-politisch interessierter Mensch ist das Thema Elternschaft, und wie diese "modern" organisiert sein soll, ein großes Anliegen. Insbesondere macht sich das Thema an Karenzzeiten und Betreuungsmodellen fest, auf die ich in den folgenden Beiträgen in Form eines Blog besonders eingehen werde.


<div id="archives">
  <section id="archive">
      {%for post in site.posts %}
	  {% if post.categories contains 'Vaeterblog' %}
      <p><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      {% endif %}
	  {% endfor %}
  </section>
</div>

## Gedanken zu verschiedenen Themen


<div id="archives">
  <section id="archive">
      {%for post in site.posts %}
	  {% if post.categories contains 'General' %}
      <p><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      {% endif %}
	  {% endfor %}
  </section>
</div>
