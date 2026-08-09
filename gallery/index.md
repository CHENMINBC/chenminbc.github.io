---
title: Gallery
nav:
  order: 4
  tooltip: Photo gallery
---

# {% include icon.html icon="fa-solid fa-images" %} Gallery

Field work and organisms photos. 田野工作与生物照片。

{% include section.html %}

## Field work

{% capture fieldwork %}

{% include figure.html image="images/gallery/work.jpg" %}
{% include figure.html image="images/gallery/lab.jpg" %}
{% include figure.html image="images/gallery/cm.jpg" %}

{% endcapture %}

{% include grid.html content=fieldwork style="square" %}


## Wildlife

{% capture wildlife %}

{% include figure.html
  image="images/gallery/redpanda.jpg"
  caption="Red panda in Sichuan"
%}

{% include figure.html image="images/gallery/waterdeer.jpg" %}
{% include figure.html image="images/gallery/babydeer.jpg" %}
{% include figure.html image="images/gallery/babywaterdeer.jpg" %}

{% endcapture %}

{% include grid.html content=wildlife style="square" %}