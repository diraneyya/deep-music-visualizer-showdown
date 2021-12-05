---
title: Noureldeen's Visualization
subtitle: Inspired by the different elements in the environment surrounding our life and how it's effected by sound.
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Noureldeen's entry for the competition.

I made one video, I was inspired by the different elements in the enviorment surrounding us and how the sound effects it.

## Command Variations

I played with the variables to test different outputs, I had to increase the smooth factor to visualize my slow music.

### Competition Entry 

```bash
   python `visualize.py` --song `song file` --resolution 512 --duration 258 \
   --pitch_sensitivity 295 --tempo_sensitivity 0.8 --depth 0.5 \
   --classes 983 980 978 966 954 928 919 889 879 857 288 107 \
   --jitter 0.5 --frame_length 512 --truncation 0.5 \
   --smooth_factor 20 --batch_size 4 --output_file `video file`

{{<video "noureldeen">}}







