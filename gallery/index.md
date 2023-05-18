---
title: Gallery
nav:
  order: 5
---

# {% include icon.html icon="fa-regular fa-envelope" %}Gallery

{% include image-gallery.html folder="/images/gallery.img" %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/joinus.img/CUHK.JPG" %}
{% include figure.html image="images/joinus.img/SBS_building.png" %}
{% include figure.html image="images/contact/cu-photo.jpg" %}

{% endcapture %}

{% include grid.html content=content style="square" %}

{% include section.html %}
