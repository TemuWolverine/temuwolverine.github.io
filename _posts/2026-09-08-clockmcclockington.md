---
layout: project
title: "ClockMcClockington"
tags: [esp32, 3d printing, open source, clock, voice]
image: /assets/images/2026-09-08-clockmcclockington.jpg
files: 
  - name: "3MF"
    link: https://makerworld.com/en/models/3282238-clock-mcclockington-esp32-smart-clock#profileId-3723050

links:
  - link: https://www.youtube.com/watch?v=fxZZN2AQnY0
    name: YouTube
    icon: youtube

  - link : https://github.com/TemuWolverine/ClockMcClockington
    name: GitHub
    icon: github
highlight:  | 
          Driven by
          * **ESP32-S3-Zero** a 'large-for-ESP32' powerhouse board, with enough accessible pins, 
          * **MAX7219** LED matrix display, 
          * **INMP441** I2S microphone,
          * **MAX98357** I2S amp, 
          * photoresistor 
          * and a few buttons
---

How hard could it be to make a smart clock?

This features my first custom designed PCB, although it really is more of a carrier board. The KiCad project and 3d model for the case are available.

I've also taken advantage of ESPHome's firmware framework to create an in [browser firmware flash utility](/ClockMcClockington/) that is automatically built upon git-push. 