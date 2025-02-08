---
title: Products
layout: page
show_excerpts: true
entries_layout: grid
---

<div class="entries-{{ page.entries_layout | default: 'list' }}">
  {% include posts-tag.html taxonomy='product' %}
</div>