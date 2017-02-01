---
layout: post
title:  "Idea Generator"
date:   2017-01-30 23:50:00
categories: Ideas
featured-img: /at_photos/photo13.jpg
---
A few ideas for new musical instruments:

**1) Waveshaper Box**

This idea would incorporate several slider potentiometers, rotary encoders, and buttons to create a waveshaping tool. The sliders can be manipulated to shape the waveform, with a pure data patch linearly interpolating between slider values. The rotary encoders at the bottom would function both as a button and as a step-wise input. The two buttons at the bottom would represent save and delete functionality.
There are two modes: edit and play. In edit mode, the user could hold the save button as well as one of the rotary encoders, which would save the current waveform into that slot (there are 8 slots for different voices). Since the rotary encoders also have LED's embedded within them, they would glow one color if the slot is empty, and another if the slot is full. In play mode, the user can play the existing voices by pressing on the rotary encoders which have a waveform stored in that slot. The sliders function as volume faders in play mode, and the rotary encoders can be incresed or decreased to change the frequency of the waveform. The interface would like similar to the sketch below:

<img src="/sketches/waveshaperSketch.jpg" alt="Waveshaper Sketch" width="600" height="400">

**2) Decision Tree**

This instrument would store several sounds or waveforms in a binary tree data structure. The instrument interface would have several buttons in the shape of the tree below, and the user would interact by pressing the buttons to choose nodes. In each node of the tree there is stored a particular waveform or recording, and the user will select which waveforms to play. The farther down the tree, the higher the frequency or pitch of the waveform. Using these buttons, the user can play each waveform polyphonically.

<img src="/assets/sketches/decisionTreeSketch.jpg" alt="Decision Tree Sketch" width="600" height="500">

**3) 12-tone Dynamic Programming**

This instrument would follow similar compositions methods to Pierre Boulez's Integral Serialism. The instrument interface would be a matrix of potentiometers and a button. There would be five iterations of programming the instrument. The first time, the user sets the pitch of each node in the matrix, next the duration, followed by the attack and release. In order to advance to the next setting, the user presses the button. Once all four have been set, the user presses the button once more in order to set the dynamic program. Here, the potentiometers represent the order in which notes will be triggered. Once set, the instrument will advance through every node using a dynamic programming algorithm, flowing from high to low. Once completed, every possible node will have been visited, playing each tone with its distinct characteristics no more than once. This process can be seen in the sketch below.

<img src="/assets/sketches/dynamicSketch.jpg" alt="Dynamic Programming Sketch" width="600" height="700">

**4) Bluetooth Sniffer**

This instrument would incorporate a bluetooth sniffer which would detect nearby bluetooth devices. The number of devices will decide the number of voices that will be synthesized. For each bluetooth device there will be a tone generated whose frequency is the rate of information being transferred or distance from the sniffer. This idea is reliant on the possibility of using a bluetooth sniffer with the Bela device.

<img src="/assets/sketches/bluetoothSketch.jpg" alt="Bluetooth Sketch" width="600" height="450">

**5) Lissajous Audio Visualizer**
This instrument would be more of a visualizer. There would be a matrix of LED's which would take audio as an input and represent a [lissajous curve](http://2.bp.blogspot.com/-3LHdNGfNq7w/VMMiVK75WyI/AAAAAAAAAhI/ujOdRL5807U/s1600/lissajous.gif). Each individual LED would light up as the lissajous spins around, creating a pleasing visual effect. I'm not sure if the Bela has enough processing power or enough inputs to do this one, but it could be an interesting attempt!

<img src="/assets/sketches/lissajousSketch.jpg" alt="Lissajous Sketch" width="600" height="340">

