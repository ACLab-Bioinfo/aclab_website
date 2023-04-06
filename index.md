---
carousels:
  - images: 
    - image: images/photo.jpg
    - image: images/photo.jpg
    - image: images/photo.jpg
    - image: images/photo.jpg
---


{% include carousel.html height="50" unit="%" duration="7" number="1" %}


{% include section.html %}

Our lab is dedicated to advancing biomedical research in hepatocellular carcinoma (HCC) immunotherapy, a novel and promising treatment approach against one of the most frequent and lethal liver cancers worldwide. We use multi-omics techniques to unravel the complex interactions in tumor microenvironment, as well as the epigenetic changes that occur during drug resistance. Our goal is to identify new biomarkers and therapeutic targets for HCC immunotherapy, and to optimize its efficacy. By applying cutting-edge technologies and collaborating with leading experts in the field, we aim to contribute to the development of personalized and effective immunotherapy strategies for HCC patients.

{% include section.html %}

## Meet our PI

{% capture text %}

{%
  include button.html
  link="members/alfred-cheng.html"
  text="Meet our PI"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/members.img/alfredcheng_3-2.png"
  link="members/alfred-cheng.html"
  title="Prof. CHENG Sze Lok Alfred (鄭詩樂)"
  flip=false
  style="bare"
  text=text
%}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="news"
  text="Check our news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="news"
  title="Our News"
  flip=true
  style="bare"
  text=text
%}


{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  icon="fa-solid fa-arrow-left"
  text="See our publications"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  flip=true
  text=text
%}

{% include section.html %}

