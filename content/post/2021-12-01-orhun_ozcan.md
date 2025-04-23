---
title: Orhun's Visualization
subtitle: Bul Beni
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Orhun's entry for the competition.

I made one video, I was inspired my last visit to Kosovo. Just the song not the snakes.

## Command Variations

I tried different things, but mainly I focused on the image classes.

### Competition Entry 1

```bash
   python `visualize.py` --song `bulbeni.wav` --resolution 128 --duration 100/
   --pitch_sensitivity 280 --depth 0.5 --num_classes 5 --classes 52 53 54 55 56/
   --jitter 0 --frame_length 2048 --smooth_factor 5/
   --output_file `orhunassignment.mp4`
```

{{<video "orhun">}}
