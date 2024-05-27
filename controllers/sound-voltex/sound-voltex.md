---
layout: default
title: Sound Voltex
description: General info on DIY Sound Voltex controllers.
parent: Controllers
nav_order: 2
redirect_from:
  - /w/Sound_Voltex
---

# Sound Voltex
{: .no_toc }

[Sound Voltex](https://remywiki.com/SOUND_VOLTEX_Information) is a rhythm game by Konami.

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Buttons

BT buttons: [60x60mm Square Buttons]({% link parts/buttons/60-60-square-buttons.md %})

FX buttons: [50x33mm Rectangle Buttons]({% link parts/buttons/50-33-rectangle-buttons.md %})

Start button: [33x33mm Square Buttons]({% link parts/buttons/33-33-square-buttons.md %})

### Switch and Spring Options

As of Valkyrie cabinets, arcade stock options are **100g switch / 20g spring**, although depending on your setup, **100g switch / 40g spring** may feel closer. Some players may prefer **50g switch / 60g spring**.

## Knobs

Possible options for encoder are listed [here]({% link parts/encoders.md %}).

Full size aluminum knobs can be purchased at:
* SpeedyLabs: [https://www.speedylabs.us/product/sound-voltex-aluminum-yuancon-diy-knob/](https://www.speedylabs.us/product/sound-voltex-aluminum-yuancon-diy-knob/)
* Blue Spring Express: [https://bluespringexpress.net/en-us/products/speedylabs-sound-voltex-aluminium-knob-for-controllers](https://bluespringexpress.net/en-us/products/speedylabs-sound-voltex-aluminium-knob-for-controllers)

Generic knobs can be found on Aliexpress, although they are smooth and not faceted.

Minicon size aluminum knobs can be purchased at:
* SpeedyLabs: [https://www.speedylabs.us/product/pocket-sdvx-aluminum-knob/](https://www.speedylabs.us/product/pocket-sdvx-aluminum-knob/)

## Code Repos

### Arduino (Atmega 32U4)

SpeedyPotato: [https://github.com/speedypotato/Pocket-SDVX/tree/master/FIRMWARE/PocketSDVX](https://github.com/speedypotato/Pocket-SDVX/tree/master/FIRMWARE/PocketSDVX)

KnucklesLee: [https://github.com/knuckleslee/RhythmCodes/tree/master/2E10B10LED_sdvx/leo](https://github.com/knuckleslee/RhythmCodes/tree/master/2E10B10LED_sdvx/leo)

4yn: [https://github.com/4yn/iivx](https://github.com/4yn/iivx)

CrazyRedMachine: [https://github.com/CrazyRedMachine/SoundVoltexIO](https://github.com/CrazyRedMachine/SoundVoltexIO)

### Raspberry Pi Pico (RP2040)

SpeedyPotato: [https://github.com/speedypotato/Pico-Game-Controller/tree/release/pocket-sdvx-pico](https://github.com/speedypotato/Pico-Game-Controller/tree/release/pocket-sdvx-pico)

## Plans and Guides

### Arcade Sized

A 3d-printed design: [https://github.com/Umi4Life/SDVX-AC-Case](https://github.com/Umi4Life/SDVX-AC-Case)

A simple laser-cut MDF guide: [https://sdvx-diy.github.io/](https://sdvx-diy.github.io/)

A simple laser-cut guide: [https://github.com/fabricioanciaes/OpenSDVXCon](https://github.com/fabricioanciaes/OpenSDVXCon)

An MDF and acrylic guide: [https://consandstuff.github.io/rhythmcons/sound-voltex/sdvx-normal/](https://consandstuff.github.io/rhythmcons/sound-voltex/sdvx-normal/)

An extremely low-cost guide (that sheds accuracy in components for budget): [https://github.com/felixha00/lowcost-voltex](https://github.com/felixha00/lowcost-voltex)

### Minicon

PCB and acrylic design: [https://github.com/mon/PocketVoltex](https://github.com/mon/PocketVoltex)

PCB and 3D printed design: [https://github.com/speedypotato/Pocket-SDVX-Pico-v4](https://github.com/speedypotato/Pocket-SDVX-Pico-v4)

3D printed design: [https://github.com/speedypotato/Pocket-SDVX](https://github.com/speedypotato/Pocket-SDVX)

## Frequently Asked Questions

### Should I buy the official Konami NESYS Controller?

It's not recommended. The entry model is all plastic with rubber dome switches. The ultimate model is higher quality, but still extremely expensive compared to DIY or third party options.

### How can I use a custom controller on SDVX Konaste (E-Amusement Cloud)?

Some codebases listed above may have this functionality built in, read the instructions. Otherwise, [this library](https://github.com/veroxzik/arduino-konami-spoof) can provide the functionality to other codebases.

### How do I set up SDVX Konaste?

See this guide: [https://voltexes.com/setting-up-sound-voltex-konasute-exceed-gear/](https://voltexes.com/setting-up-sound-voltex-konasute-exceed-gear/)

### Do I need Sanwa buttons?

As with any hobby, it's possible to put in as much money as you want! Sanwa buttons are the highest quality option, but they are not necessary to play, enjoy, and score well in the game. 

### Can I add Turbocharger-style LEDs to my controller?

Take a look at this library: [https://github.com/veroxzik/sdvx-led-strip](https://github.com/veroxzik/sdvx-led-strip)
