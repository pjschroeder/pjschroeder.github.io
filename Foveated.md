### Welcome to the official website of Foveated Photos
---
layout: default
images:
  - image_path: Foveated/images/AUS7_thumb.jpg
    title: New Zealand
  - image_path: Foveated/images/AUS8_thumb.jpg
    title: Auckland
  - image_path: Foveated/images/BE_thumb.jpg
    title: Bruges
  - image_path: Foveated/images/BER0_thumb.jpg
    title: Bermuda
  - image_path: Foveated/images/BON0_thumb.jpg
    title: Bonaire
  - image_path: /images/cakes/chocolate-cake.jpg
    title: Chocolate Cake
  - image_path: /images/cakes/fruit-cake.jpg
    title: Fruit Cake
  - image_path: /images/cakes/lamington.jpg
    title: Lamington
  - image_path: /images/cakes/lemon-cake.jpg
    title: Lemon Cake
---
...
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ Foveated/images }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
