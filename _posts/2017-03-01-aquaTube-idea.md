---
layout: post
title:  "AquaTube Idea"
description: "An instrument idea involving water in a tube"
date:   2017-03-01 14:00:00
tags: [projects, bela, aquaTube, pure data, ideas]

share: false
---
The idea I've decided to pursue involves water or liquid inside a clear acrylic tube. This idea originated as an instrument contained within a water bottle, but I think a longer plastic tube will yield better results. The device will use two [liquid level sensors](https://www.sparkfun.com/products/10221), two [force sensitive resistors](https://www.sparkfun.com/products/9375), two [contact microphones](https://en.wikipedia.org/wiki/Contact_microphone), and two [buttons](https://www.sparkfun.com/products/10442) to create sound.

{% capture sketch %}
  /images/aquaTube/aquaTube-sketch.jpg
{% endcapture %}
{% include gallery images=sketch caption="aquaTube Sketch" cols=2 %}

The user will hold the tube horizontally, with their hands on the caps on either end. On each cap there will be both a tactile button and a force sensitive resistor (FSR). There will also be two LED's on the inside of each cap: one red and one ultraviolet. Inside the tube there will be two contact microphones and two water level sensors, one on each side. Below the tube there will be a small box which will contain the bela, a breadboard, and the bela's power source.

The user will press the button to record a sample of the contact microphone on that side, recording the sloshing, bubbling, watery sounds. When recording, the red LED will turn on, causing the tube to glow red. When the user releases the button, the recording will be saved into a buffer in PD on the Bela. When the user presses the FSR, it will trigger repetitive playback of the recorded sample. The harder the user presses the FSR, the louder the playback will be. The frequency of this sample playback will be determined by the water level sensor. When a sample is being played, the UV LED will glow according to how hard the FSR is pressed. The tube will be filled with some sort of liquid that glows under blacklight (tonic water or flourescent paint mixed with water), so the whole tube will glow blue when the sound is played. 
