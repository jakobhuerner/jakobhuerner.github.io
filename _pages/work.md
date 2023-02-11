---
layout: page
title: Work
permalink: /work/
---

After my school and university education within technology and industrial engineering, I started my career in an international group in the steel industry. While already 10 years with the company, I had a wide variety of roles within industrial management, based at the group's Vienna headquarters and at a production site in Sweden.

At the moment, I am leading a team of highly skilled and dynamic individuals that drives strategic topics within our global company group.

Over the years I have developed an increasing interest in all things digital, both by taking on roles concerning digitalisation and by postgraduate education in Data Science.

In the course of my career I helped shaping activities and programs that significantly increase efficiency and reduce the environmental footprint of the company group. I develop teams and programs within the global company network and establish completely new capability fields for the group. 

## My strength

I see my core strength in "connecting the dots". I am good at identifying patterns in unfamiliar, opaque and messy situations. I enjoy most when I am able to successfully re-apply proven ideas and concepts from foreign fields, after understanding their similarities with the problem at hand.

![Jakob's strength](../images/work_jakob_strength.jpg)

Going hand in hand with the point above, I am always interested in understanding systems below the surface, the systems' actors, and their connections. Only by understanding systems and their dynamics, you are able to effectively shape them in a permanent and sustainable way.


## Professional blog

I am writing about various aspects of my work, new work and career in this section.

It not only helps me reflect on my challenges and my professional development. I also want to share my experiences so that others can benefit from it. 

### List of posts

<div id="archives">
  <section id="archive">
      {%for post in site.posts %}
	  {% if post.categories contains 'ProfessionalBlog' %}
      <p><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{%endif%}</p>
      {% endif %}
	  {% endfor %}
  </section>
</div>