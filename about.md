---
layout: page
title: We're FUN
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

### <center>你是宇宙里最特别的那颗星</center>

### <center>只被我看见的那部分天真</center>

</div>
