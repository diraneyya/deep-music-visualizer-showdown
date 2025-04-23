---
title: saeed's Visualization
subtitle: Inspired by my Dutch party visitations in Sittard
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Orwa's entry for the competition.

I made three videos, I was inspired by the type of music I heard in the _Soulfully Yours_ parties in Holland.

## Command Variations

I tried different things, the tempo command seems to help me achieve what I wanted to achieve because of this and that.

### Competition Entry 1

```bash
   python `visualize.py` --song `song file` --batch_size 3 --duration 25 \
   --resolution 256 --pitch_sensitivity 290 --jitter 1 \
   --classes 847 483 668 724 652 413 269 403 319 353 603 354 \
   --output_file `video file`
```

{{<video "saeed-1">}}

### Competition Entry 2

```bash
   python `visualize.py` --song `song file` --batch_size 3 \
   --classes 847 483 668 724 652 413 269 403 319 353 603 354 \
   --resolution 512 --jitter 1 --output_file `video file`
```

{{<video "saeed-2">}}