---
title: Dominik's Visualization
subtitle: Inspired by Berlin's underground techno parties
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Dominik's entry for the competition.

I made two videos, I was inspired by the type of music I heard at the _underground techno parties_ in Berlin.

## Command Variations

Techno music has high bpm's and a fast pitch change. The video has to be able to follow the fast changes accorddingly, so it is important to adjust the python code to it. The visuals have to support the atmosphere of the music, that's why the pictures have a fast flow and don't stay static. 

### Anetha - Acid Train
```bash
python 'visualize.py' --song `song file` --resolution 512 --pitch_sensitivity 1 \
 --tempo_sensitivity 0.8 --depth 1 --classes 25 50 75 150 200 400 450 550 670 699 802 969 \
 --jitter 0 --frame_length 512  --truncation 0.9 --smooth_factor 5 --batch_size 4 --output_file 'video file'
```

{{<video "dominik-1">}}

### Faithless - Insomnia

```bash
visualize.py --song `song file` --resolution 256 --pitch_sensitivity 299 --tempo_sensitivity 0.1 --depth 0.4 \
--classes 9 38 57 99 145 256 437 666 786 834 890 912 --num_classes 10 --jitter 0.5 --frame_length 1024 \ 
--truncation 0.4 --smooth_factor 25 --batch_size 5 --output_file `video file`
```

{{<video "dominik-2">}}