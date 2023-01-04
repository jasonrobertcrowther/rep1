---
layout:     post
date: 2022-11-19
#description: "the nitty gritty"
#featured_image: "https://source.unsplash.com/aWrkBDjpxQ8"
title: "Livestream test"
tags:
    - Youtube
    - livestream
    - portfolio
    - basketball
author: "Dan"
showthedate: false
weight: 101
series : ["Video"]
---

This was an experiment in live streaming and person following

My instant thought when doing a livestream is OBS and a laptop and a camera feed. While this can work very well we were looking at how we could stream a live event easily with minimal equipment and also minimal space (and potentially minimal operator skills set) 

We found an Aver tracking camera that can track people or objects. What we wanted to do was evaluate the effectiveness of this when livestreaming a basketball game. As an added bonus the camera can also send its output to any RTMP streaming destination.

We took the Aver Camera on a tripod, an IPad Mini, a mini network switch and wifi access point and paired all of this up with a mobile hotspot on a phone

We quickly found that the auto tracking capabilities of the camera were not able to keep up with the fast motion of a basketball game (even though this was a training session).

We then changed the configuration to create 6 presets on the camera which were controllable from the IPad using an Aver software App

Each preset covered a large area of the hall and so the operator was able to move to another preset in plenty of time as the action moved up and down the court. It took a while for the operator to get used to the controls but once they were used to the lag between selecting the preset and it actually moving it was quite effective.

{{< youtube 60XQ470HcRQ >}}

From 1:43:00 onwards you can see the concept of the camera moving to the operator requests - with the operator not needing to be physically next to the camera and you can see the operator becoming more familiar as the mini game progresses

All the time during our tests, the camera was live streaming. The Aver camera is able to send an RTMP stream directly to any capable service (in this case YouTube) without the requirement for a PC running live streaming software.

The stream was set to 720p and this was still able to stream without buffering live using around 2Mbs of bandwidth using the mobile phone hotspot.

The video above was not an exercise in editing - it was more of a proof of concept. Also note that there is no sound in this video - again it was primarily an exercise in streaming.

Coincidentally, all the time that the stream was running a remote coach was able to comment and give feedback on the session.

