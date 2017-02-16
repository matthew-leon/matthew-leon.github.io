---
layout: post
title:  "Beeping Bela"
description: "My first Bela patch, featuring 2 digital inputs, 2 digital outputs, and 2 analog inputs."
date:   2017-02-14 14:00:00
tags: [projects, bela, 3d printing, pure data]
share: false
---
**Beeping Bela**

For my first project using the [Bela](http://bela.io), I 3D-printed an enclosure to fully contain the bela, and all its wiring and inputs. In order to create this case, I found an [existing box for the Beaglebone Black](http://www.thingiverse.com/thing:102399) and modified its SCAD file to make it much taller. You can download this modified SCAD file and associated files [here][1].

After printing the case, I realized the Bela would not fit with such high walls. After feverishly trying to stuff the Bela into the cylinder, I decided to separate the cylinder and the and bottom part of the case by sawing it off entirely.

{% capture case %}
  /images/beeping-bela/case-bottom.jpg
  /images/beeping-bela/case-middle-side.jpg
  /images/beeping-bela/case-middle.jpg
{% endcapture %}

{% include gallery images=case caption="The bottom and sides of the case" cols=3 %}

Once I had the case printed, I drill pressed some holes in the lid for access to potentiometers, buttons, LED's and the audio jack. I then glued and screwed all the components to the lid for a sturdy fit. 

{% capture lid %}
  /images/beeping-bela/top-view.jpg
  /images/beeping-bela/under-lid-wire.jpg
  /images/beeping-bela/under-lid-glue.jpg
{% endcapture %}

{% include gallery images=case caption="The lid with inputs and outputs attached" cols=3 %}


Check out the PD patch [here][2].



<img src="/images/beeping-bela/beeping-bela-patch.jpg" 	alt="Sketch for Bela patch" width="auto" height="500">

<img src="/images/beeping-bela/bela-top.jpg" 			alt="Sketch for Bela patch" width="auto" height="auto">
<img src="/images/beeping-bela/disassembled.jpg" 		alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/proto-pins-bottom.jpg" 	alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/proto-pins-side.jpg" 	alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/proto-pins.jpg" 			alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/proto-side.jpg" 			alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/proto-top-close.jpg" 	alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/proto-top.jpg" 			alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/side-ethernet.jpg" 		alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/side-usb.jpg" 			alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/side-view.jpg" 			alt="Sketch for Bela patch" width="auto" height="550">
<img src="/images/beeping-bela/top-angle.jpg" 			alt="Sketch for Bela patch" width="auto" height="550">

[1]:{{ site.url }}/downloads/beagleCase.zip
[2]:{{ site.url }}/downloads/pd-patches/beeping-bela.pd
