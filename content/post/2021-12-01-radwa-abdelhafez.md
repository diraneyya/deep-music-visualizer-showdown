---
title: Radwa's Visualization
subtitle: Inspired by Egyptian Classic music
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Radwa's entry for the competition.

I made one video, inspired by classical egyptian composer named OmarKhairat .

## Command Variations

I tried different things, the tempo command seems to help me achieve what I wanted to achieve because of this and that.

### Competition Entry 1

```bash
   python `visualize.py` --song `omarkhairat` --batch_size  --duration 40 \
   --resolution 128 --pitch_sensitivity 290 --jitter 1 \
   --classes 847 483 668 724 652 413 269 403 319 353 603 354 \
   --output_file `video file`
```

{{<video "radwa">}}

http://localhost:1313/deep-music-visualizer-showdown/post/2021-12-01-radwa-abdelhafez/