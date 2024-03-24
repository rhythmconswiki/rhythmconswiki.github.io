---
layout: default
title: YuanCon 
parent: Commercial Controllers
nav_order: 2
has_children: true
redirect_from:
  - /w/YuanCon_FAQ
  - /w/Yuan_FAQ
---

# YuanCon
{: .no_toc }

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## General Frequently Asked Questions

This section lists frequently asked questions related to YuanCon controllers, intended to consolidate the information spread across the YuanCon Discord server. You should also check the [Maintenance FAQ]({$ link getting-started/maintenance-faq.md $}) page.

[This page](https://oniichan.wtf/help/) may also contain helpful information, although much of the information is outdated for newer controllers.

Also note that despite releasing after the SDVX 12, the SDVX Lite (Gen 1 and 2) is considered to come before the SDVX 12 because it uses an older controller PCB. 

### Where can I get firmware updates?

See [YuanCon Firmware]({$ link commercial/yuancon/firmware.md $}).

### How do I update the firmware on my controller?

See [YuanCon Firmware]({$ link commercial/yuancon/firmware.md $}).

## Sound Voltex FAQ

### How do I set up the controller for SDVX EAC/Konasute?

Use mode 3 and don't bind anything. See [#What are the different modes for YuanCon SDVX controllers?](#What are the different modes for YuanCon SDVX controllers?)

For controllers prior to the SDVX 12, including the SDVX Lite (1 and 2/+), install the latest firmware for compatibility. See [YuanCon Firmware]({$ link commercial/yuancon/firmware.md $}).

### How do I set up the controller for USC?

Use mode 3 and configure the game to use controller input for both buttons and knobs, then bind the controls.

### How do I set up the controller for KSM?

Use mode 1 and bind the controls.

### What are the different modes for YuanCon SDVX controllers?

YuanCon controllers have 4 different modes. To change modes, unplug the controller, hold down the corresponding button(s) for the mode, plug in the controller, and continue holding until the lights flash. For older controllers (prior to SDVX 12, including SDVX Lite), holding Start in addition to the corresponding button is needed for modes 1, 2, and 3 (i.e. BT-C for mode 3 on SDVX 12, Start+BT-C for mode 3 prior to SDVX 12).

**Mode 1** [BT-A] (Mouse and Keyboard mode):

In this mode, the buttons will send key presses and the knobs will move the mouse cursor.

**Mode 2** [BT-B] (Mouse and Gamepad mode):

In this mode, the buttons will behave as a gamepad device but the knobs will still move the mouse cursor. This is a very uncommon mode to use.

**Mode 3** [BT-C] (Gamepad/EAC mode):

In this mode, the buttons and knobs will behave as a gamepad device, with the knobs moving the gamepad's joystick. Except for old controllers without firmware update, the controller spoofs Konami's official Sound Voltex controllers in this mode, so it can be used with EAC/Konasute with no configuration.

**Update Mode** [FX-L+FX-R]:

This mode allows the controller to receive firmware updates. This doesn't apply to YuanCon SDVX 12 controllers. **Note for SDVX Lite controllers: if you try to use FX-L+FX-R and the lights do not flash, then you are not in update mode. Try using the side buttons instead. This is one of the problems that the update fixes.**

### What are the buttons on the side for?

The side buttons are extra general-purpose buttons that you can bind to anything you want. On the SDVX 12, they also control lighting modes for the controller, and are referred to as EX 1 (farther from the knobs) and EX 2 (closer to the knobs).

#### SDVX 12

Hold EX1 and pressing EX2 will cycle through the available modes:

* Mode 1 All four light bars will flow in a rainbow of colours
* Mode 2 four light bars will always be in the colour you have adjusted. Press Ex2 and turn the knob to adjust the color
* Mode 3 four light bars will show dynamic colours you have adjusted. Press Ex2 and turn the knob to adjust the color
* Mode 4 Turn off all lights

#### SDVX Old Model and Lite

Hold the side button on the right and press the Start button to cycle through the available modes 

* Mode 1 Light off
* Mode 2 Static colour lights, press the side button and the turn any knob to change the colour of the light
* Mode 3 Breathing lights, press the side button and the turn any knob to change the colour of the light
* Mode 4 Breathing lights with RGB

### Can I remap the keys/buttons that the controller sends as inputs?

You can change which header each button plugs into on the PCB, but you can't arbitrarily assign keys. Note that doing so will break native EAC/Konasute compatibility.

As a workaround, you can use mode 3 with a program like Joy2Key to remap the inputs in software rather than in firmware.

### What are the extra springs that came with the controller?

These are the default springs that came with the Chinese buttons in the controller. They are extremely heavy, at about 200-300g of force, and are unsuitable for play. They're included as an extra just for the sake of it.

### The knobs on my older controller aren't behaving right, how do I fix it?

This is a problem that affects controllers prior to the SDVX 12, using the old controller PCB. The firmware was written so that regardless of how fast you spin the knobs, the output speed was always constant, as opposed to being 1:1. This technically "works" but is incorrect and inaccurate behavior.

To fix it, install the 2021-12-05 firmware update or newer. See [YuanCon Firmware]({$ link commercial/yuancon/firmware.md $}).

### How do I use HID lights with the controller?

YuanCon does not currently support HID lights for any SDVX controllers.

## beatmania IIDX FAQ

### How do I set up the controller for Infinitas?

Use mode 3 and don't bind anything. See [#What are the different modes for YuanCon IIDX controllers?](#What are the different modes for YuanCon IIDX controllers?)

### How do I set up the controller for beatoraja?

Use mode 3, enable analog scratch, and bind the controls.

See also:
* [Analog scratch configuration](https://github.com/wcko87/beatoraja-english-guide/wiki/Configuration#analog-scratch)
* [I connected my controller but my turntable doesn't work!](https://github.com/wcko87/beatoraja-english-guide/wiki/FAQ-and-Troubleshooting#i-connected-my-controller-but-my-turntable-does-not-work)

### What are the different modes for YuanCon IIDX controllers?

By pressing the following key combinations before plugging in the controller you can change the modes for the Yuancon IIDX controller 

**WIP**

**Mode 1** [5+7(Old controller) or Start(DX5th)]

Keyboard mode, scratch binded to mouse

**Mode 2** [5+6(Old controller) or Select(DX5th)]

Controller mode with digital scratch

**Mode 3** [5+4(Old controller) or VEFX(DX5th)]

Infinitas mode with analog scratch

## Controllers

Click one of the options below: