---
title: Music Player
sidebar:
    label: " - Music Player"
---

:::tip
Make sure to read about [playing music in SplashKit](/book/part-1-instructions/1-sequence-and-data/2-trailside/11-3-audio) for this task.
:::

We can use sequence and data to play around with the sound playing features of SplashKit. This program will ask the user to enter the path to a sound effect to play, how long to play it for, an initial volume and a final volume. This will then output messages saying what it is doing, while it plays the music.

```txt
Welcome to the music play test

What file would you like to load? Enter path: /Users/andrew/Downloads/test.ogg
What should I call this music? Enter name: Test1

Loading Test1 music from /Users/andrew/Downloads/test.ogg

How long do you want to play it for? Enter seconds: 30
At what initial volume? Enter percent (0 to 1): 0.50
At what repeat volume? Enter percent (0 to 1): 1.00

Playing Test1 at 0.5 volume for 30 seconds...
Stopping music

Playing Test1 at 1.0 volume for 30 seconds...
Stopping music
```

:::tip[Where can I get a file?]
You can download this [sample audio](https://programmers.guide/resources/code-examples/part-0/hello-world-snippet-saddle-club.ogg) file.
:::