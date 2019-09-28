---
layout: page
title: 图集
permalink: /imgs/
published: true
---

<div class="page" >

{% capture page_subtitle %}

{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

<center>🤨</center>

<center>每个灵魂都半人半鬼</center>

</div>

<img src="http://images.weserv.nl/?url=funzmr.github.io/Remember{{ page.image }}&w=200&h=200&output=jpg&q=65" />

{% include image-gallery.html folder="/uploads" %}
