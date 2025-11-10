---
title: MrWatson's Blog
strapline: Tell me about it!
parent: MrWatson.de
layout: default
nav_order: 002
---

{% include page-image.html width=site.page_image_width %}

# {{page.title}}

{{page.strapline}}

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url }}) <span class="post-date">{{post.date | date: "%d.%m.%Y"}}</span>

{{ post.excerpt }}

{% endfor %}
