---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

<p style="text-align:center;">
We are looking for Post Doc and Graduated Students.<br>
Please feel free to contact us if you want to join or visit our lab!!
</p>

{%
  include button.html
  type="email"
  text="jiamingsmu1333@smu.edu.cn"
  link="jiamingsmu1333@smu.edu.cn"
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
link="https://www.google.com/maps/place/Southern+Medical+Univ+Shenzhen+Hosp/@22.5416453,113.8961272,16z/data=!4m6!3m5!1s0x3403ee8503ac66ad:0x6441175ca0a07c33!8m2!3d22.5444!4d113.89661!16s%2Fg%2F11p5v56tq5?entry=ttu&g_ep=EgoyMDI1MDgwNi4wIKXMDSoASAFQAw%3D%3D"

%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/nyd.png"
  caption="Our Hospital"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/googlemap.png"
  caption="Our Location"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}
