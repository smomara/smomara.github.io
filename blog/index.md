---
layout: default
title: Sean O'Mara - Blog
---

# Blog

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*
> {{ post.excerpt }}
{% endfor %}
