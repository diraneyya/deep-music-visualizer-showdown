---
title: Seongho's Visualization
subtitle: Inspired by my Dutch party visitations in Sittard
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---


This is Seongho's entry for the competition.

I made two videos, I was inspired by the type of music I heard in the _Soulfully Yours_ parties in Holland.

## Command Variations

I tried different things, the tempo command seems to help me achieve what I wanted to achieve because of this and that.

### Competition Entry 1

```bash
   python `visualize.py` --song `Dies Irae` --batch_size 4 --duration 46 \
   --resolution 512 --pitch_sensitivity 200 --tempo_sensitivity 0.5 --depth 0.3 --jitter 0.2 \
   --classes 1 2 3 4 5 6 7 8 9 10 11 12 --frame_length 512 --truncation 0.6 --smooth_factor 2\
   --output_file `ha-1`
```

{{<video "ha-1">}}

### Competition Entry 2

```bash
   python `visualize.py` --song `New World` --batch_size 4 --duration 46 \
   --classes 24 77 86 47 85 97 72 63 43 45 66 92 --frame_length 512 --truncation 0.6 --smooth_factor 2 \
   --resolution 512 --pitch_sensitivity 200 --tempo_sensitivity 0.5 --depth 0.3 --jitter 0.2 --output_file `ha-2`
```

{{<video "ha-2">}}