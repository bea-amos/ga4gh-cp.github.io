---
title:  'Implementation Minutes Archive'
date: 2018-05-23
author: mbaudis
layout: default
permalink: /minutes-implementation.html
category:
  - implementation
tags:
  - featured
---

## GA4GH::CP {{ page.title }}

The (combined) current meeting minutes are published accessible through [here](https://docs.google.com/document/d/1Qfms-6C8z1sFcjbhtcdpeUeAyeFF6vmGjX7sGCV3DEs/edit) for review and comments.

### Archive

{% for item in site.categories.implementation %}
  {% if item.tags contains 'minutes' %}
    {% assign currentyear = item.date | date: "%Y" %}
    {% if currentyear != currentdate %}
<h2 id="y{{ currentyear }}">{{ currentyear }}</h2>
      {% assign currentdate = currentyear %}
    {% endif %}
<div class="excerpt">
{{ item.excerpt }}
<p>{{ item.date | date: "%Y-%m-%d" }}: <a href="{{ item.url | relative_url }}">more ...</a></p>
</div>
  {% endif %}
{% endfor %}
