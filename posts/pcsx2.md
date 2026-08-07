---
layout: default
title: Emulator zone - PCSX2 overview
description: 2 August 2026
image: img/gta3-1.png
---

# Basic setup 

![Grand Theft Auto III PCSX2 Screenshot](../img/gta3-1.png)
*PCSX2 screenshot*

My goal with this setup was to recreate a native PS2 look. More specifically, I wanted to feel as though I was playing the game on original hardware without the image appearing too sharp or upscaled. PCSX2 is configured to native 4:3 resolution by default, which is great.

# Why not use original hardware?

![Silent Hill 2 PS2 Screenshot](../img/sh2-1.png)
*PS2 screenshot*

I own a PS2 console and have the capability to capture footage, however, my cheap [AV2HDMI upscaler](https://www.amazon.co.uk/dp/B08RMVMB2G) and [USB capture card](https://www.amazon.co.uk/dp/B089D8DB44) do a poor job of converting the signal. Even when sharpened in OBS, it doesn’t look good. There’s also the issue of switching between HDMI inputs on my one monitor setup. I can see a preview in OBS but there is a risk of input delay. I might consider upgrading my setup at some point.

# PCSX2 advantages

![Grand Theft Auto III PCSX2 Screenshot](../img/gta3-3.png)
*PCSX2 screenshot*

The advantage of using PCSX2 is that you can use a PS5 controller via USB. Crucially, you can monitor OBS as you play without needing to switch to another HDMI input. There is the option of upscaling the game to FHD or even 4K in 16:9 widescreen. You also don’t need to worry about cable management.

# Lag issue: Solved 

I encountered an issue where the audio lagged very noticeably as the game loaded. I fixed the issue by changing the graphics API to Direct3D 11. The graphics API is set to automatic by default. I can only assume that the emulator was opting for a graphics renderer that put too much strain on my PC. If you encounter a similar problem this might be worth checking.

---

*Note - I own a PS2 console and physical copies of the games featured in this article. I do not endorse piracy. You can find out more about the PCSX2 emulator [here](https://pcsx2.net/)*
