---
title: "A New Controller - using the Wiimote for Free Gesture Performance"
date: "2007-12-24"
---

A week before the N.I.P. crew arrived at Amsterdam I was already at [Steim](http://www.steim.org/), experimenting with a new controller for my performances.

Since I’m mainly interested in free gesture interfaces, like the Theremin, this new controller is also using this principle.

For some time I ruled out tracking systems based on computer-vision because I felt most of them were inappropriate for the level of interaction I desired. They were always too dependent on environmental conditioning (like light) or two slow or imprecise. Usually I’ve tried out using 320x240 video matrixes, with CPU based blob detection and so. These systems never fully satisfied me and that’s why the Airstick is based on physical IR optical rangers, with much more responsive rates. Nevertheless the Airstick also has it’s own restrictions, the biggest being the lower resolution of the x-axis, which results of the horizontal sensor array distribution.

A month or so ago I saw an experiment of [Johnny Lee](http://www.cs.cmu.edu/~johnny/), from the HCI group at the Carnegie Mellon University. He’s been doing interesting experiments with the Wiimote and he explained how the tracking system for the Wiimote works. Basically it has on-board blob detection of up to four IR points at a resolution of 1024x768. This makes it much more precise than the typical webcam approach and the hardware blob calculation is much faster than the CPU correspondent.

This turned me into experimenting with this and I ended up building these small IR led fingers that I point at the Wiimote. With two leds in each hand I can control two different 3D objects, with position (x,y), angle rotation and size.

{{< figure src="led-fingers1.jpg" title="" lightbox="true" >}}


It’s looking good and I think I’ll try to incorporate these into my next performance to happen on the 18th January, in Lisbon. Soon I'll post a You Tube video of a demo.

Lastly thanks to the STEIM crew for having me. They create the perfect environment for this type of experimentation. Special kudos to Jorgen Brinkman for all his patience in bearing with me!
