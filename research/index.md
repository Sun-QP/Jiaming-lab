---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

<p style="text-align:center;">
We are doing some great and awesome bone researches with tremendous sea of love
</p>

{% include section.html %}

## Highlighted

{% include citation.html lookup="doi:10.1186/s12951-023-02050-7"  style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% assign recent_citations = "" | split: "" %}
{% for c in citations %}
  {% assign year = c.date | slice: 0, 4 %}
  {% if year >= "2022" %}
    {% assign recent_citations = recent_citations | push: c %}
  {% endif %}
{% endfor %}

{% include list.html data=recent_citations component="citation" style="rich" %}
