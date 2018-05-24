---
title:  'Representation Minutes Archive'
date: 2222-11-11
layout: default
permalink: /minutes-representation.html
category:
  - representation
---

## GA4GH::CP Representation Minutes Archive

The (combined) current meeting minutes are published accessible through [here](https://docs.google.com/document/d/1Qfms-6C8z1sFcjbhtcdpeUeAyeFF6vmGjX7sGCV3DEs/edit) for review and comments.

### Archive

{% for item in site.tags.representation_minutes %}
<div class="excerpt">
{{ item.excerpt }}
<p>{{ item.date | date: "%Y-%m-%d" }}: <a href="{{ item.url | relative_url }}">more ...</a></p>
</div>
{% endfor %}
