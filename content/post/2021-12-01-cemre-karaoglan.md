---
title: Cemre's Visualization
subtitle: Two Faces of Istanbul
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Cemre's entry for the competition.

Two aspects of the culture and of my life in Istanbul condensed into two songs.

## Command Variations

Working with different genres of songs and playing with the parameters accordingly gave me the most interesting results.

### Competition Entry 1

```bash
   python `visualize.py` --song `quesera.wav` --resolution 512 --pitch_sensitivity 280 --tempo_sensitivity 0.6 --depth 0.7 --batch_size 4
```

{{<video "cemre-1">}}

### Competition Entry 2

```bash
  python visualize.py --song 'zuluf.wav' --resolution 512 --pitch_sensitivity 200 --tempo_sensitivity 0.3 \
  --depth 0.5 --jitter 0.8 --truncation 0.7 --batch_size 4 --num_classes 12 --classes 471 1 84 56 94 323 325 282 288 292 54 64`
```

{{<video "cemre-2">}}