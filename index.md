---
title: MrWatson.de
strapline: Maker of Tools making FileMaker work
nav_order: 001
layout: default
---
{% include page-image.html width=site.page_image_width %}

# {{page.title}}

{{page.strapline}}

## Latest News

{%capture posts %}
{% for post in site.posts limit:3 %}

### <span class="post-date">{{post.date | date: "%d.%m.%Y"}}</span> [{{ post.title }}]({{ post.url }})

{{ post.excerpt }}

{% endfor %}

 [more →](blog.html)
 {% endcapture %}<section class="posts">{{ posts | markdownify }}</section>

## Quick Links

| [![fmWorkMate.de](https://fmworkmate.com/fmworkmate.png){: .button-image }](https://fmworkmate.com) | [![GitHub mrwatson-deProfile](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png){: .button-image }](https://github.com/mrwatson-de) | [![YouTube Channel](https://www.youtube.com/s/desktop/932eb6a8/img/favicon_144x144.png){: .button-image }](https://www.youtube.com/@FMWorkmate) |
|:---:|:---:|:---:|
| [fmWorkMate.com](https://fmworkmate.com) | [GitHub @MrWatson-de](https://github.com/mrwatson-de) | [fmWorkmate YouTube Channel](https://www.youtube.com/@FMWorkmate) |
