---
title: Yasmin's Visualization
subtitle: Inspired by my Special dates and childhood fav song
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Yasmin's entry for the competition.

I made this video, I was inspired by one of my childhood favorite songs _Dessert Rose_ in Egypt.

## Command Variations

I tried different things, I run out of memory and i tried to change the batch size to get it work.

### Competition Entry

```bash
   python `visualize.py` --song `song file` --batch_size 4 --duration 60 \
   --resolution 512 --pitch_sensitivity 220 --jitter 1 \
   --classes 169 662 199 234 197 23 19 21 40 200 10 1 \
   --output_file `video file`
```

{{<video "yasmin">}}

