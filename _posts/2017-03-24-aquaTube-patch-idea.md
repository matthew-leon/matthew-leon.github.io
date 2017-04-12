---
layout: post
title:  "AquaTube Patch Idea"
description: "A preliminary patch diagram for the aquaTube instrument."
date:   2017-03-24 12:30:00
tags: [projects, bela, pure data, aquaTube]

share: false
---

This is a preliminary patch for the aquaTube instrument. It uses two analog variable resistors (water level sensors), two digital buttons, two analog force sensitive resistors (FSR's), two contact microphones, and has two UV LED outputs as well as a small speaker and 1/4" audio output.

Pressing and holding a button will begin recording audio from the contact microphone into a buffer. Once the button is released, the recording stops. When the FSR is pressed, the audio will begin to playback on a loop. The strength of the FSR press will directly correlate to the volume of playback and will also trigger the LED which will be dimmer on a lighter press and brighter on a stronger press. The frequency of the playback will correlate to the water level sensor value.

This will be the same on both sides of the instrument, creating a polyphonic sound.

{% capture sketch %}
  /images/aquaTube/aquaTube-patch-idea.jpg
{% endcapture %}
{% include gallery images=sketch caption="aquaTube patch idea" cols=2 %}
