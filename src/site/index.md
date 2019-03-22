---
meta_description: John Kellyn Resman is a designer from Kansas City who specializes in digital strategy, user experience, and product design.
layout: layouts/base.njk
bodyClass: home
title_site: John Resman
title_meta: UX strategy & product design
---

<div class="content">
<div class="intro">

# John Resman
## Product Designer
[About](/about)

</div>

<div class="feed feed-notes">

<h4 class="section_hdr">Latest notes</h4>

<ul>
  {%- for post in collections.post -%}
    <li class="card"><a href="{{ post.url }}">{{ post.data.title }}<br/><time class="date" datetime="{{ date }}">{{ date | dateDisplay }}</time></a></li>
  {%- endfor -%}
</ul>

</div>

<div class="feed feed-work">

<h4 class="section_hdr">Latest work</h4>

</div>
</div>
