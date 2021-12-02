---
title: Emad's Visualization
subtitle: Inspired from the national anthem of the ottoman Empire.
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Emad's entry for the competition.

I made a lot of videos (a couple of failed attempts)

## Command Variations

I tried different things, because i didn't have a good GPU drive i tried to restrict the process time so i selected the following options --batch_size 3 
--duration 25 
--resolution 256 
--pitch_sensitivity 290

I wanted to select images classes which present this big empire so I selected
- 847: 'tank, army tank, armored combat vehicle, armoured combat vehicle',
- 483: 'castle',
- 668: 'mosque',
- 724: 'pirate, pirate ship',
- 652: 'military uniform',
- 413: 'assault rifle, assault gun',
- 269: 'timber wolf, grey wolf, gray wolf, Canis lupus',
- 403: 'aircraft carrier, carrier, flattop, attack aircraft carrier',
- 319: "dragonfly, darning needle, devil's darning needle, sewing need"le, snake feeder, snake doctor, mosquito - hawk, skeeter hawk",
- 353: 'gazelle',
- 603: 'horse cart, horse-cart',
- 354: 'Arabian camel, dromedary, Camelus dromedarius',


### Competition Entry 

```bash
  python `visualize.py` --song `song file` --batch_size 3 --duration 25 --resolution 256 --pitch_sensitivity 290 --classes 847 483 668 724 652 413 269 403 319 353 603 354 --jitter 1 --output_file Emad_Aldoghry

{{<video "aldoghry">}}
```

