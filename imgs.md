---
layout: page
title: 图集
permalink: /imgs/
published: true
---

<div class="page" >

{% capture page_subtitle %}
<!-- 可以加一个音乐播放器 -->
	{% include externals/searchbox.html %}
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

<center>最好的我们</center>

{% include externals/image-gallery.html folder="/uploads" %}

</div>
