---
layout: page
permalink: /personal/
title: Personal
---

Der Fokus dieses Bereichs liegt auf persönliche Themen rund um Familie und Elternsein.

_Er ist in Deutsch gehalten, da diese Themen  direkt mit dem Umfeld und rechtlichen Rahmenbedingungen in Österreich verbunden sind und damit im Wesentlichen nur für deutschprachige Leserinnen und Leser von Interesse sein wird._ 


Für mich als Vater und gesellschaftlich-politisch interessierter Mensch ist das Thema Elternschaft, und wie diese "modern" organisiert sein soll, ein großes Anliegen. Insbesondere macht sich das Thema an Karenzzeiten und Betreuungsmodellen fest, auf die ich in den folgenden Beiträgen in Form eines Blog besonders eingehen werde.

## Väterblog

Die Beiträge geben meine Erfahrungen und persönlichen Meinungen wieder.


<div id="archives">
  <section id="archive">
      {%for post in site.posts %}
	  {% if post.categories contains 'Vaeterblog' %}
      <p><b><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a></b> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      {% endif %}
	  {% endfor %}
  </section>
</div>