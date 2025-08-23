---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html %}
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

<center> <h3 style="font-size: 2rem; margin: 1rem 0;">Our Cherish Time</h3> </center>

{% include section.html %}

{% capture content %}

{% include figure.html image="images/team1.jpg" caption="Two handsome boys in front of a monument!" %}
{% include figure.html image="images/roasting.jpg" caption="delicious roasted beef" %}
{% include figure.html image="images/computer.jpg" caption="Thank you Dr Xiong for helping us assemble our first computer" %}

{% endcapture %}

{% include grid.html style="square" content=content %}









