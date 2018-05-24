---
title:  'Implementation Minutes Archive'
date: 2222-11-11
layout: default
permalink: /minutes-implementation.html
category:
  - implementation
---

## GA4GH::CP Implementation Minutes Archive

The (combined) current meeting minutes are published accessible through [here](https://docs.google.com/document/d/1Qfms-6C8z1sFcjbhtcdpeUeAyeFF6vmGjX7sGCV3DEs/edit) for review and comments.

### Archive

{% assign today = site.time | date: '%s' %}

{% for item in site.tags.exchange_minutes %}
  {% assign postStartDate = item.date | date: '%s' %}
  {% assign currentyear = item.date | date: "%Y" %}
  {% unless postStartDate > today %}
    {% if currentyear != date %}
<h2 id="y{{item.date | date: "%Y"}}">{{ currentdate }}</h2>
      {% assign date = currentyear %}
    {% endif %}

<div class="excerpt">

{{ item.excerpt }}

  <p>{{ item.date | date: "%Y-%m-%d" }}: <a href="{{ item.url | relative_url }}">more ...</a></p>
</div>

  {% endunless %}
{% endfor %}
