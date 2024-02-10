---
layout: page
title: Work
permalink: /work/
---

I currently work as department head in a large Austrian industrial company. In my 10+ years there I had a wide variety of roles at the group's Vienna headquarters and at a production site in Sweden.

In the course of my career I helped shaping activities and programs that significantly increase efficiency and reduce the company's environmental footprint. I focus on initiatives with global reach and establish completely new capability fields for the group. 

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