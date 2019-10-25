---
layout: layouts/post.njk
title: About Me
tags:
  - nav
  - page
navtitle: About
templateClass: tmpl-post
---

I am a person that writes stuff.

<ul>
{%- for page in collections.page -%}
  <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
{%- endfor -%}
</ul>
