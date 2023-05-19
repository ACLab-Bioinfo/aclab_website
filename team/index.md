---
title: Team
nav:
  order: 4
---

# {% include icon.html icon="fa-solid fa-users" %}Team


Welcome to our lab and get to know our team! Our laboratory members are from different background, and all are passionate about our work and committed to advancing scientific knowledge in their respective fields. 


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ra" filters="role: rasso" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" filters="role: ^(?!ra$)" filters="role: ^(?!rasso$)" filters="group: current" %}


{% capture content %}

  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}
  
{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}

{:.center}
----- Former Lab Members -----

| Name   | Lab Position        | Current Position                        |
| ------ | ------------------- | --------------------------------------- |
| Test   | Ph.D. Student       | test                                    |
| Test   | Postdoctoral Fellow | test                                    |


