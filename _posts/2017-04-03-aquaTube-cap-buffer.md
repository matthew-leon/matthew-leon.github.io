---
layout: post
title:  "AquaTube Cap Buffer"
description: "The cap won't fit!"
date:   2017-04-03 12:30:00
tags: [projects, bela, pure data, aquaTube, 3d printing]

share: false
---

Well, I've run into an annoying problem, as expected. The [PVC caps](https://www.amazon.com/NDS-3P06-Sewer-Drain-3-Inch/dp/B006H3U4R8/) I ordered do not fit onto the [plastic tube](https://www.amazon.com/gp/product/B000OMHJQ2/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1) as I had expected. The caps are listed as 3 inches in diameter, but in reality they are 3.25 inches in diameter. This poses a bit of a problem in terms of waterproofing. In order to fix this issue, I have designed a [3D-printed ring][1] which serves as a buffer between the tube and the cap. The ring needs a bit of sanding around the edges to make it fit perfectly, but once on the tube it's a pretty great fit!

[1]:{{ site.url }}/downloads/aquaTube/cap-buffer-2.0.stl

{% capture buffer %}
  /images/aquaTube/cap-buffer.JPG
  /images/aquaTube/tube+pvc.JPG

{% endcapture %}
{% include gallery images=buffer caption="Cap Buffer" cols=4 %}
