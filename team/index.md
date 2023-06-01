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

{% include list.html data="members" component="portrait" filters="role: postdoc" filters="role: visit"%}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: phd" filters="role: undergrad" %}


{% capture content %}

  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}
  {% include figure.html image="images/photo.jpg" %}
  
{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}


## Former Lab Members 


| Name   | Lab Position        | Current Position                        |
| ------ | ------------------- | --------------------------------------- |
| Test   | Ph.D. Student       | test                                    |
| Test   | Postdoctoral Fellow | test                                    |


<table style="width:90%">
<colgroup>
<col width="25%" />
<col width="35%" />
<col width="40%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Lab Position</th>
<th>Current Position</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">First column **fields**</td>
<td markdown="span">Some descriptive text. This is a markdown link to [Google](http://google.com). Or see [some link][mydoc_tags].</td>
<td markdown="span">third column **fields**</td>
</tr>
<tr>
<td markdown="span">Second column **fields**</td>
<td markdown="span">Some more descriptive text.</td>
<td markdown="span">Some more descriptive text.</td>
</tr>
</tbody>
</table>