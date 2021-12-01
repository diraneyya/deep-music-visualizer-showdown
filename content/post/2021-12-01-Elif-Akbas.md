---
title: Elif's Visualization
subtitle: Inspired by my Dutch party visitations in Sittard
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Orwa's entry for the competition.

I made two videos, I was inspired by the type of music I heard in the _Soulfully Yours_ parties in Holland.

## Command Variations

I tried different things, the tempo command seems to help me achieve what I wanted to achieve because of this and that.

### Competition Entry 

```bash
   python `visualize.py` --song `song file` --batch_size 4 --duration 35 \
   --pitch_sensitivity 290 \
   --classes 431 435 448 472 512 542 625 626 638 644 701 724 \
   --output_file `video file`
```

{{<video "elif">}}