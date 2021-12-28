# PiP locked screen bug demo

This is a demonstration of a lock screen bug in PiP on iOS.

To reproduce:
1. Build and launch app
2. Play "Video 1"
3. Invoke PiP
4. Lock device screen
5. ... video (sound) keeps playing

This repo differs from Apple's [*Adopting Picture in Picture Playback in tvOS*](https://developer.apple.com/documentation/avkit/adopting_picture_in_picture_playback_in_tvos) only in that we've added an audio track to `video1.m4v`.

-----
# Adopting Picture in Picture Playback in tvOS

Add advanced multitasking capabilities to your video apps by using Picture in Picture playback in tvOS.

## Overview

- Note: This sample code project is associated with WWDC20 session [10176: Master Picture in Picture on tvOS](https://developer.apple.com/videos/play/wwdc2020/10176/).

## Requirements
This sample code project must be run on a physical device.
