---
title: Contact
nav:
  order: 4
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d616.7916784018629!2d114.20382012963337!3d22.427440701512552!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3404089018f1d2b9%3A0xbaeb2c45830d7f66!2z5rKZ55Sw572X5qGC56Wl57u85ZCI55Sf54mp5Yy75a2m5aSn5qW8!5e0!3m2!1szh-CN!2shk!4v1678882950249!5m2!1szh-CN!2shk"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}


