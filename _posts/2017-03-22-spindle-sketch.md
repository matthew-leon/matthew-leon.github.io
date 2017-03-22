---
layout: post
title:  "Spindle Instrument Idea"
description: "A synthesis instrument using conductive pegs"
date:   2017-03-22 12:30:00
tags: [ideas, bela, pure data, spindle]

share: false
---

This instrument would feature several wooden spindles which each correlate to a different type of waveform. One spindle would contain a sine wave, one would contain a sawtooth wave, one would contain a square wave, etc. Each wooden spindle would be wrapped in some conductive material -- maybe copper foil. Each spindle would emerge from the base unit which would house all the electronics, as well as a connector to the cradle selector. 

The cradle selector would have several holes corresponding to the number and shape of the spindles. The spindle cradle will be lined with a conductive material as well, so placing the cradle on a spindle will result in a closed circuit, which can be recognized by the Bela. Each spindle cradle hole corresponds to a certain sound effect, such as reverb, chorus, flanger, distortion, etc. The cradle selector would also have a photoresistor and a button next to each slot. 

In order to perform the instrument, the user would place the cradle on the spindles in one of many different placements. Each cradle becomes a voice that can be triggered by pressing the button, with the photoresistor changing the frequency of the waveform associated with that spindle. Depending on which spindle is touching which cradle, that waveform will be processed by the effect of the associated cradle. When a cradle is not connected to a spindle, it becomes a wet/dry parameter using the photoresistor as input. 

In order to play 

{% capture sketch %}
  /images/sketches/spindle-sketch.jpg
{% endcapture %}
{% include gallery images=sketch caption="spindle sketch" cols=2 %}
