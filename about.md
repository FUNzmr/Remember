---
layout: page
title: FUN
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## <center>🤨</center>

## <center>每个灵魂都半人半鬼</center>

<form method="POST" action="https://formspree.io/YOUREMAILHERE">
  <input type="email" name="email" placeholder="Your email">
  <textarea name="message" placeholder="输入您想说的话"></textarea>
  <button type="submit">发送</button>
</form>

</div>
