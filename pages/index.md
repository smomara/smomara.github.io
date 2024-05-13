---
layout: default
title: Sean O'Mara - Pages
---

## Books

{% for book in site.data.books %}
- [{{ book.title }} by {{ book.authors }}]({{ book.link }})
  - {{ book.description }}
{% endfor %}

## Resources

{% for resource in site.data.resources %}
- [{{ resource.title }}]({{ resource.link }})
  - {{ resource.description }}
{% endfor %}

## Essays

{% for essay in site.data.essays %}
- [{{ essay.title }} by {{ essay.author }}]({{ essay.link }})
  - "{{ essay.quote }}"
{% endfor %}