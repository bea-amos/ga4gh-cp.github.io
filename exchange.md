---
title:  "Exchange & Interoperability"
layout: default
permalink: /exchange.html
category: exchange
---

## {{ page.title }}

Below are links to posts related to GA4GH::CP "{{ page.title }}". The minutes of meetings of the subgroup can be found [here](/minutes-exchange.html).

---

{% for item in site.categories.exchange %}
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
