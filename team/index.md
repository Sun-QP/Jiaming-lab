---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

### Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html %}

{% include section.html %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}




{% include section.html background="images/background.jpg" dark=true %}

### Our Cherish Time

{% include section.html %}

{% capture content %}

{% include figure.html image="images/team1.jpg" caption="Two handsome boys in front of a monument!" %}
{% include figure.html image="images/roasting.jpg" caption="delicious roasted beef" %}
{% include figure.html image="computer/photo.jpg" caption="Thank you Dr Xiong for helping us assemble our first compute" %}

{% endcapture %}

{% include grid.html style="square" content=content %}









