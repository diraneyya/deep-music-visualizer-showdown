---
title: Radwa's Visualization
subtitle: Inspired by Classic Egyptian Music 
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Radwa's entry for the competition.

I made a video inspired by Egyptian classical composer called Omar Khairat.

## Command Variations

I tried different things, the tempo command seems to help me achieve what I wanted to achieve because of this and that.

### Competition Entry 1

```bash
   python `visualize.py` --song `song file` --batch_size 3 --duration 25 \
   --resolution 256 --pitch_sensitivity 290 --jitter 1 \
   --classes 847 483 668 724 652 413 269 403 319 353 603 354 \
   --output_file `video file`
```

{{<video "radwa">}}