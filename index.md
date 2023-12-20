---
layout: default
---

On December 30, 2021, our house and all of our belongings burned down in the Marshall Fire.

Thank you for supporting us. Please see the posts below for updates. Here are links to support us and our community directly:

* [Our GoFundMe](https://www.gofundme.com/f/superior-watts-recovery-fund)
* [Our Amazon wishlist](https://www.amazon.com/hz/wishlist/ls/2LL3FYQESWG0U)
* [Our Venmo](https://venmo.com/u/PhilRW)
* [Marshall Fire Family Relief Fund](https://www.gofundme.com/f/boulder-superior-louisville-fire-relief-fund)
* [Photo album of progress](https://photos.rosenberg-watt.com/s/2a8h5l4y1a/rebuild)

# Posts

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">
        {{ post.excerpt }}

      {% if post.excerpt != post.content %}
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
      {% endif %}
      </div>
    </article>
  {% endfor %}
</div>
