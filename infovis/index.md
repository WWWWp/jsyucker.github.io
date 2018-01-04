---
layout: article
title:  "期末可视化"
excerpt："就两个"
tags: []
date:   2018-01-02 
categories: infovis
image:
  teaser: visualization.jpg
  feature: visualization.jpg
---


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->