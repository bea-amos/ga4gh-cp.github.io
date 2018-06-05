---
title:  "Data Representation"
layout: default
permalink: /representation.html
category: representation
---

## {{ page.title }}


[Criteria list for resources evaluation](/representation/criteria.html)


Below are links to posts related to GA4GH::CP "{{ page.title }}". The minutes of meetings of the subgroup can be found [here](/minutes-representation.html).

---

{% for item in site.categories.representation %}
  {% unless item.date > site.time %}
    {% assign year_current = item.date | date: "%Y" %}
    {% if year_current != year_label %}
<h3 id="y{{ year_label }}">{{ year_label }}</h3>
      {% assign year_label = year_current %}
    {% endif %}
<div class="excerpt">
{{ item.excerpt }}
<p>{{ item.date | date: "%Y-%m-%d" }}: <a href="{{ item.url | relative_url }}">more ...</a></p>
</div>
  {% endunless %}
{% endfor %}
