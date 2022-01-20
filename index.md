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

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      {% if post.excerpt != post.content %}
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
      {% endif %}
    </article>
  {% endfor %}
</div>

<div class="posts">
  {% for post in site.posts %}
    <article class="post" markdown="1">
## [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
      <div class="entry" markdown="1">
{{ post.excerpt }}

      {% if post.excerpt != post.content %}
[Read More]({{ site.baseurl }}{{ post.url }})
      {% endif %}
      </div>
    </article>
  {% endfor %}
</div>

