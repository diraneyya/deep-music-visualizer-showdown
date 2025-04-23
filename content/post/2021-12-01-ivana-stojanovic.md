---
title: Ivana's Visualization
subtitle: Inspired by the famous Northern Macedonia´s fast 7/8 rhythm
date: 2021-12-01
tags: ["music-visualizer", "competition"]
---

This is Ivana's project video made by deep-music-visualizer.

I made four videos. I experimented with parametars and the last one proved to be the best one.

## Command Variations

The tempo was very important as the rhythm is quite fast. I was also trying to get in the video more pictures of the people than animals, but in the end I gave up and just used random numbers. Somehow this way I got 2 pictures with people, compered with my previous tries which had none. 

### Competition Entry 1

```bash
   python `visualize.py` --song `Jovano_Jovanke.wav` 
   --resolution 512 
   --duration 30 
   --pitch_sensitivity 220 
   --tempo_sensitivity 0.5 
   --depth 0.7 
   --classes 44 111 222 333 444 555 666 777 888 999 21 13 
   --jitter 0.5 
   --batch_size 4 
   --output_file `my_song_4.mp4`

```

{{<video "ivana">}}
