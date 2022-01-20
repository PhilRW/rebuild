---
layout: default
---

Thank you for supporting us. Please see the posts below for updates. Here are links to support us and our community directly:

* [GoFundMe](https://www.gofundme.com/f/superior-watts-recovery-fund)
* [Amazon wishlist](https://www.amazon.com/hz/wishlist/ls/2LL3FYQESWG0U)
* [Venmo](https://venmo.com/u/PhilRW)
* [Marshall Fire Family Relief Fund](https://www.gofundme.com/f/boulder-superior-louisville-fire-relief-fund)

# Posts

<div class="posts">
{% for post in site.posts %}
<article class="post">
## [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
<div class="entry">
{{ post.excerpt }}
</div>
{% if post.excerpt != post.content %}
<div class="read-more">[Read More]({{ site.baseurl }}{{ post.url }})</div>
{% endif %}
</article>
{% endfor %}
</div>

# {{ site.data.links.title }}

{% for item in site.data.links.docs %}
* [{{ item.title}}]({{ item.url }})
{% endfor %}
