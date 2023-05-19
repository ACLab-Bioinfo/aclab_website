---
title: Gallery
nav:
  order: 5
---

# {% include icon.html icon="fa-regular fa-envelope" %}Gallery

{% capture content %}
  {% include figure.html image="images/photo.jpg" title = "Test1" %}
  {% include figure.html image="images/photo.jpg" title = "Test2" %}
  {% include figure.html image="images/photo.jpg" title = "Test3" %}
{% endcapture %}

{%
  include cols.html
  content=content
  style="square"
%}