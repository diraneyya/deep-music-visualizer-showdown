---
title: Timur's Visualization
subtitle: Inspired by some music I found online 
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Timur's entry for the competition.

I made two videos, I was inspired by some license-free music tracks I found online.

## Command Variations

I did some trial and error changing various different settings for the deep music visualizer and combining it with animal as well as spacecraft image libraries.

### Competition Entry 1

```bash
   python visualize.py --song 8-bit_game_theme.wav --resolution 512 --duration 30 --pitch_sensitivity 240 --tempo_sensitivity 0.3 --depth 0.9 --num_classes 1 --classes 812 --sort_classes_by_power 1 --jitter 0.65 --frame_length 512 --truncation 0.5 --smooth_factor 16 --batch_size 30 --use_previous_classes 0 --use_previous_vectors 0 --output_file 8bit_game_theme_video.mp4
```

{{<video "timur-1">}}

### Competition Entry 2

```bash
   python visualize.py --song lo-fi_guitar.wav --resolution 512 --duration 30 --pitch_sensitivity 250 --tempo_sensitivity 0.45 --depth 0.75 --num_classes 6 --sort_classes_by_power 1 --jitter 0.75 --frame_length 512 --truncation 0.8 --smooth_factor 22 --batch_size 30 --use_previous_classes 0 --use_previous_vectors 0 --output_file lo-fi_guitar_video.mp4
```

{{<video "timur-2">}}