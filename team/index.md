---
title: Team
nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-users" %}Team


Welcome to our lab and get to know our team! Our laboratory members are from different background, and all are passionate about our work and committed to advancing scientific knowledge in their respective fields. 


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% capture content %}

  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}
  
{% endcapture %}


{% include section.html background="images/background.jpg" dark=true %}
{:.center}
Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filters="group: alum" %}


{% include grid.html style="square" content=content %}
