---
show: false
width: 4
date: 2020-01-12 00:01:00 +0800
---
<div>
  <img data-src="{{ 'assets/images/photos/portrait.jpg' | relative_url }}" class="lazy w-100 rounded-xl" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">

  <div class="card-img-overlay " style="overflow: hidden; background-color: rgba(0, 0, 0, 0.5);">
    <h5 class="card-title">Image Lazyload</h5> 
    <p class="card-text">
      It is highly recommended to use lazyload for images to improve page loading speed, especially for pages with many images.
      Example code snippet:
    </p>
    <p class="card-text">
      {% raw %}
      <code>&lt;img data-src=&quot;[Image URL]&quot; class=&quot;lazy w-100 rounded-xl&quot; src=&quot;{{ '/assets/images/empty_300x200.png' | relative_url }}&quot;&gt;</code>
      {% endraw %}
    </p>
  </div>
</div>
