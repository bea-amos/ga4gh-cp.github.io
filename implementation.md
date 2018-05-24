---
title:  "Implementation & Engagement"
layout: default
permalink: /implementation.html
category: implementation
---

## {{ page.title }}

Below are links to posts related to GA4GH::CP "{{ page.title }}". The minutes of meetings of the subgroup can be found [here](/minutes-implementation.html).

---

{% for item in site.categories.implementation %}
  {% assign currentdate = item.date | date: "%Y" %}
  {% if currentdate != date %}
<h3 id="y{{item.date | date: "%Y"}}">{{ currentdate }}</h3>
   {% assign date = currentdate %}
  {% endif %}
<div class="excerpt">
{{ item.excerpt }}
<p>{{ item.date | date: "%Y-%m-%d" }}: <a href="{{ item.url | relative_url }}">more ...</a></p>
</div>
{% endfor %}
