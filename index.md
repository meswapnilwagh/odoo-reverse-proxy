---
title: Odoo - Reverse Proxy HowTo
author: Swapnil Wagh
layout: default
---

{% for post in site.posts reversed %}
<section class="slide antiun-slide" id="{{ post.label }}">
{{ post.content }}
</section>
{% endfor %}
