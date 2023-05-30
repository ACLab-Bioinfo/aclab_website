---
carousels:
  - images: 
    - image: images/photo.jpg
    - image: images/photo.jpg
    - image: images/photo.jpg
    - image: images/photo.jpg
---

{% include carousel.html height="20" unit="%" duration="7" number="1" %}




{% include section.html %}

{% capture text %}
As ***E***pigenetics and ***T***herapeutics in ***I***mmuno-***O***ncology refer, our laboratory aims at identifying the cause (*etio* in Greek) and solution of cancer therapeutic resistance. On the one hand, we apply the cutting-edge single-cell multi-omics and AI innovation to understand tumor adaptation to immune-checkpoint blockade (ICB) and uncover the epigenetic and transcriptional programs underlying immunotherapeutic resistance. On the other hand, we develop effective and durable combination immunotherapies for clinical translation. A prime example is a novel class I HDAC-targeted epigenetic immunotherapy, which has secured governmental and industrial support to commence a Phase-II clinical trial for hepatocellular carcinoma patients resisting to ICB therapy. Through collaborations with leading experts in the field, our research is expected to have major impact in both basic research and treatment for this fatal cancer.  
{% endcapture %}

{%
  include feature.html
  image="images/main.img/mainpage.etio.png"
  link="research"
  text=text
%}

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
  title="Prof. CHENG Sze Lok Alfred 鄭詩樂教授"
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
  text="See our research"
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

