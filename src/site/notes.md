---
meta_description:
layout: layouts/base.njk
title:
title_meta:
bodyClass: notes
---


<ul>
  {%- for post in collections.post -%}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
  {%- endfor -%}
</ul>
