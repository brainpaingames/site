---
title: "Hypershack - Moving in 4d"
date: 2023-03-30
category: Tutorials
---

This post explains how to move in 4d in hypershack, and assumes you have launched hypershack as explained in previous tutorial (link here).

First, what does it mean to move in 4d in hypershack? In hypershack, the 3d space you observe around you is a cross-section of a 4d hyperspace. In the observable 3d space you can move around in a space thait spanned by your forward, right and up vectors. You can also rotate around forward-right (yaw), forward-up (pitch), and right-up (roll) planes. In addition to these 3d movements, you can manipulate  the 3d cross-section in the fourth dimension. As there are no well established terms for the directions in the fourth dimension, they are called here "hither" for direction towards negative w axis and "thither" for positive w axis. So, you can move the 3d corss section hither or thither. You can also rotate your observed 3d cross-section in forward-thither, up-thither and right-thither planes. 


Keyboard bindings
=================

For now, keyboard is the only supported input device for moving around in 4d. Below are the current defualt keyboard bindings. Non-qwerty layout may make them a bit challenging, remappable bindings are on the roadmap.

- w - move forward
- s - move backwards
- a - yaw to left (rotate on xz plane) 

Navigation helpers
==================

As the navigation in a space with 4 spatial dimensions is a bit unnatural for most of us, there are some navigation aids built in the simulation.

Acoustic sensory augmentation
-----------------------------

There are sound beacons for positive x, y, z, and w axis:

- x: dog barking
- y: fff
- w: ggg
- z: hhh

The closer the axis is aligned with your observed 3d space, the louder the beacon is. So if you are completely aligned on x, y and z axes and w axis is perpendicular to your observed 3d space, you will not hear hhh at all, and the other beacons are all on full volume. 


Compass
-------

In addition to the sound beacons, there is a visual compass. the compass has rods pointing towards the projection of each of the four axis in the observed 3d space. The length of the rods depend on how well aligned the axis is with the observed 3d space. If the axis is perpendicular to the 3d space, the length of the rod is zero, and it grows longer as you rotate towards being more algned with the axis.  

- x: black
- y: blue
- w: red
- z: yellow





Example video here on moving with the default 5cell to all directions






