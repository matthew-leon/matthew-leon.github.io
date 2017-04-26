---
layout: post
title:  "AquaTube PVC Cap"
description: "A cap to separate electronics and water"
date:   2017-04-12 12:30:00
tags: [projects, bela, pure data, aquaTube, 3d printing]

share: false
---

I've encountered another hurdle. How do I separate electronics and water? A solution I've thought of is to 3D-print a housing cap to hold all the electronics that will fit onto the [PVC cap](https://www.amazon.com/NDS-3P06-Sewer-Drain-3-Inch/dp/B006H3U4R8/). As sketched out in the schematic below, this printed cap would attach to the PVC cap and would have enough room for the wires and electronics to be safely separated from the water. I've designed a [3D-printed cap][1] with a divider ring to fit snugly onto the PVC cap. This should work well to contain all the electronics. I will use a drill press and a dremel to bore holes in the end for wires and buttons.

Here's what it looks like with the microphone, LED's and water level sensor installed: 

[1]:{{ site.url }}/downloads/aquaTube/pvc-cap-3.0.stl

{% capture cap %}
  /images/aquaTube/pvc1.JPG
  /images/aquaTube/pvc2.JPG
  /images/aquaTube/pvc+mic.JPG
  /images/aquaTube/pvc+sensor.JPG
  /images/aquaTube/cap1.JPG
  /images/aquaTube/cap2.JPG
  /images/aquaTube/cap+hose1.JPG
  /images/aquaTube/cap+hose2.JPG
  /images/aquaTube/cap+hose3.JPG
  /images/aquaTube/cap+tube1.JPG
  /images/aquaTube/cap+tube2.JPG
  /images/aquaTube/cap+valve.JPG

{% endcapture %}
{% include gallery images=sketch caption="aquaTube cap" cols=5 %}
