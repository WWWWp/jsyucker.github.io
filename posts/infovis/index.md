---
layout: archive
title: "可视化笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "我要留校"
tags: []
image: 
  feature: web.jpg
  teaser:
---


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->