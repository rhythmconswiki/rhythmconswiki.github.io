---
layout: default
title: beatmania IIDX
description: General info on DIY beatmania IIDX controllers.
parent: Controllers
nav_order: 1
redirect_from:
  - /w/Beatmania_IIDX
---

# beatmania IIDX
{: .no_toc }

[Beatmania IIDX](https://remywiki.com/Beatmania_IIDX_Information) is a rhythm game by Konami.

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Buttons

Main gameplay buttons: [50x33mm Rectangle Buttons]({% link parts/buttons/50-33-rectangle-buttons.md %})

Menu buttons: [33x33mm Square Buttons]({% link parts/buttons/33-33-square-buttons.md %})

### Switch and Spring Options

As of Lightning cabinets, arcade stock options are **50g switch / 50g spring**, and prior to that, switch and spring options varied greatly depending on preference of local arcade players. DP players may prefer a lighter spring.

## Code Repos

### Arduino (Atmega 32U4)

Gladuin: [https://github.com/Gladuin/iidx-controller](https://github.com/Gladuin/iidx-controller)

KnucklesLee: [ttps://github.com/knuckleslee/RhythmCodes/tree/master/1E11B11LED_iidx/leo](https://github.com/knuckleslee/RhythmCodes/tree/master/1E11B11LED_iidx/leo)

Inorizushi: [https://github.com/Inorizushi/funni-IIDX](https://github.com/Inorizushi/funni-IIDX)

4yn: [https://github.com/4yn/iivx](https://github.com/4yn/iivx)

### Raspberry Pi Pico (RP2040)

SpeedyPotato: [https://github.com/speedypotato/Pico-Game-Controller/tree/release/pocket-iidx](https://github.com/speedypotato/Pico-Game-Controller/tree/release/pocket-iidx)

## Controller Size

Several sizes of controllers have been designed and released over the years.

### Arcade Style

Arcade-Style Controllers (ASC for short), use the same measurements as the official arcade machine. The DJ Dao Phoenixwan and YuanCon DX controllers are built to this specification.

### KOC

Konami Original Controllers (KOC for short) refer to a series of home controllers made by Konami for PS2 and later PC. These controllers feature a smaller turntable, and depending on the model, the distance from turntable to buttons may be smaller. All KOC feature rubber dome buttons instead of arcade switches.

### FPS

DJ Dao's FPS controller is another popular size for smaller controllers, using a KOC sized turntable but arcade-accurate distance from turntable to buttons.

## Plans and Guides

### Arcade Sized

A full sized controller designed for laser cutting: [https://github.com/Infecta/Controller-LaserCut-CAD](https://github.com/Infecta/Controller-LaserCut-CAD)

### Smaller Controllers

GJ-Tho Modular, a 3d-printed controller with full sized keypad and smaller turntable: [https://www.thingiverse.com/thing:6286147](https://www.thingiverse.com/thing:6286147)

GJ-Tho Portable, a 3d printed controller with full sized keypad and very small turntable: [https://www.thingiverse.com/thing:6050384](https://www.thingiverse.com/thing:6050384)

IIDX Pico, a 3d printed design focused on portability: [https://github.com/whowechina/iidx_pico](https://github.com/whowechina/iidx_pico)

Teeny IIDX, a 3d printed design that folds up: [https://github.com/whowechina/iidx_teeny](https://github.com/whowechina/iidx_teeny)

The **Cons & Stuff** site has a smaller design: [https://consandstuff.github.io/rhythmcons/beatmania-iidx/iidx-small/](https://consandstuff.github.io/rhythmcons/beatmania-iidx/iidx-small/)

## Frequently Asked Questions

### Which controller size should I choose?

Arcade style is recommended if you plan on switching between a real arcade cabinet and home play, or if you don't have a size constraint. Smaller controllers are more suitable for smaller living spaces.

### Can I use my DIY controller on Infinitas or Ultimate Mobile?

Some codebases listed above may have this functionality built in, read the instructions. Otherwise, [this library](https://github.com/veroxzik/arduino-konami-spoof) can provide the functionality to other codebases.
