---
layout: layout.njk
title: 目次
---

# 目次

<ul>
{%- for page in collections.page -%}
  <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
{%- endfor -%}
</ul>
