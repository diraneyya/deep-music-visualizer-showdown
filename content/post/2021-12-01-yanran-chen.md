---
title: Yanran's Visualization
subtitle: Inspired by an Opera in Shanghai
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

### Competition Entry 1

```bash
   python `visualize.py` --song `song file` --duration 43 --depth 0.5 \
   --batch_size 4 --pitch_sensitivity 220 \
   --tempo_sensitivity 0.07 --num_classes 8 --frame_length 1024 \
   --truncation 0.1 --smooth_factor 40 --jitter 0.2 \
   --output_file `video file`
```

{{<video "yanran">}}