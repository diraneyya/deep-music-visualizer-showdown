---
title: Erich's Visualization
subtitle: Assassin's Creed Soundtrack visualized with my Architecture Background
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Erich's entry for the competition.

I made three videos, I love the Assassin's Creed 2 Soundtrack, so I used Pictures which represent my Architecture Background.

## Command Variations

I finally made it! The quality is better. By adding " --batch_size 5 " I was able to increase the resolution to 512. Still, I think my first ones are better because they stimulate the imagination and more often capture the mood better.I finally made it! The quality is better. By adding " --batch_size 5 " I was able to increase the resolution to 512. Still, I think my first ones are better because they stimulate the imagination and more often capture the mood better.

### Competition Entry 1

```bash
   python `visualize.py` --song `song file` --resolution 128 \
   --pitch_sensitivity 250 --num_classes 7 \
   --classes 497 22 535 624 668 825 821 --output_file `video file`
```

{{<video "erich-1">}}

### Competition Entry 2

```bash
   python `visualize.py` --song `song-file` --resolution 128 \
   --pitch_sensitivity 150 --num_classes 7 \
   --classes 497 22 535 624 668 825 821 --output_file `viedo file`
```

{{<video "erich-2">}}

### Competition Entry 3

```bash
   python `visualize.py` --song `song-file` --resolution 512 \
   --pitch_sensitivity 150 --num_classes 7 \
   --classes 497 22 535 624 668 825 821 --batch_size 5 --output_file `video file`
```

{{<video "erich-3">}}