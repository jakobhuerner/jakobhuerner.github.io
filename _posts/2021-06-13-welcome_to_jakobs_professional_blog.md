---
layout: post
title: Welcome to Jakob’s professional blog
categories: [ProfessionalBlog]
excerpt: Start of my professional blog about work and life-long learning
image: /images/professionalblog/20210613.jpg
---

![Jakob’s Professional blog](../images/professionalblog/20210613.jpg)

I started this blog to share my thoughts on this major theme:

> What I have learnt and still need to learn on my professional journey from an industrial engineer to a digitalisation lead, and later a head of department.

## Motivation

All my life I liked exchanging ideas and teaching. On the one hand to pass on my knowledge, on the other hand to understand the matter better by reflecting it and explaining it in different ways. My aim for this blog is to help others with best practices in fields I consider myself experienced and knowledgeable, and at the same time to get a more well-rounded understanding of those areas myself.

## List of posts

<div id="archives">
  <section id="archive">
      {%for post in site.posts %}
	  {% if post.categories contains 'ProfessionalBlog' %}
      <p><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      {% endif %}
	  {% endfor %}
  </section>
</div>

## Looking forward to hearing from you

I am interested in discussing all statements I make! However, I want to point out that there is no single right or wrong in most of those topics. I will only engage in discussions that extend the field of view in the matter, and will not comment on offensive comments or statements that I do not consider relevant to the topic.

All content presented in this blog reflects my personal opinion and experience and does not necessarily represent my employers' or other partners' points of view. 


If you would like to read more about my work, check out the [work page](../work).
