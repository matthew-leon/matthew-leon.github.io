---
layout: post
title:  "Waveshaper Update"
description: "An update to the waveshaper idea."
date:   2017-02-22 14:00:00
tags: [projects, bela, waveshaper, pure data]
image:
  feature: /images/waveshape.bmp
share: false
---
**Waveshaper Update**

After thinking more about my [waveshaping idea](https://matthew-leon.github.io/idea-generator/), I have made some updates. First off, the Bela cannot handle the number of inputs I mentioned in the post, but with less inputs there would be a loss in the waveshaping quality. To account for this I have sketched out some other possibilities.
{% capture sketch %}
  /images/sketches/waveshaper-update-sketch.jpg
{% endcapture %}
{% include gallery images=sketch caption="Waveshaper Sketch" cols=2 %}

The first sketch involves two slider potentiometers and a button to toggle overwriting. The horizontal slider will cycle through the array slots, and the vertical slider will correspond to the amplitude value at that slot. The button will dictate when to overwrite at the corresponding sample index.

The second sketch shows a similar concept but using a circle. This would have a rotary encoder in the center, with a piece of string tied to it and some sort of knob that is in a circular groove. This would allow the user to spin the peg or knob around the circle, rotating the encoder and drawing a sinusoid into the table.

The last small thought would be to use a [magnetometer sensor](https://www.sparkfun.com/products/12670). This sensor from Sparkfun can sense the X/Y/Z coordinates of a magnet and could be useful for this project. By holding a magnet over the surface, I could draw the waveform in the air, resulting in a clearer wavetable.
