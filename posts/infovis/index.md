---
layout: archive
title: "可视化笔记"
date: 2018-01-04
modified:
excerpt: "我要留校"
tags: []
image: 
  feature: visualization.jpg
  teaser:
---


<div class="tiles">
{% for post in site.categories.infovisbiji %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovisbiji 的列出来-->