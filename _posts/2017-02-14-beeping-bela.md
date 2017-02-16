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

{% include gallery images=lid caption="The lid with inputs and outputs attached" cols=3 %}

I then prepared a [proto-cape](https://www.sparkfun.com/products/12774) for the beaglebone by soldering headers pins onto the sides and soldering the inputs onto the board. Since the analog inputs on the bela are covered by the board, I pushed the wire connected to the potentiometers through the board into the bela's inputs.

{% capture proto %}
  /images/beeping-bela/proto-pins-bottom.jpg
  /images/beeping-bela/proto-pins-side.jpg
  /images/beeping-bela/proto-pins.jpg
  /images/beeping-bela/proto-side.jpg
  /images/beeping-bela/proto-pins.jpg
  /images/beeping-bela/proto-top-close.jpg
  /images/beeping-bela/proto-top.jpg
{% endcapture %}

{% include gallery images=proto caption="The proto-cape" cols=7 %}

Once everything was soldered together, I attached the cape and all the inputs and shoved everything into the box. 

{% capture final-product %}
  /images/beeping-bela/disassembled.jpg
  /images/beeping-bela/side-ethernet.jpg
  /images/beeping-bela/side-usb.jpg
  /images/beeping-bela/side-view.jpg
  /images/beeping-bela/top-angle.jpg
{% endcapture %}

{% include gallery images=final-product caption="The finished product!" cols=7 %}

Once everything was in the box, I started working on the [Pure Data](https://puredata.info) patch. I wanted something that would randomly generate tones based on the analog and digital inputs and would generate some sort of meaningful response from the LED's. Below is a rough sketch of the patch I created:

{% capture patch %}
  /images/beeping-bela/beeping-bela-patch.jpg
{% endcapture %}

{% include gallery images=patch caption="A sketch of the PD patch" cols=1 %}

Check out the PD patch [here][2].

Video performance coming soon!


[1]:{{ site.url }}/downloads/beagleCase.zip
[2]:{{ site.url }}/downloads/pd-patches/beeping-bela.pd
