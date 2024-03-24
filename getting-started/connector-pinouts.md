---
layout: default
title: Connector Pinouts
parent: Getting Started
nav_order: 7
redirect_from:
  - /w/Connector_Pinouts
---

# Connector Pinouts
{: .no_toc }

This page lists a few common connector pinouts for different commercial vendors. 

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## General Info

For the purposes of this page:

* Button pins will be marked as Switch or LED.
  * Switch pins should go to the microswitch on the NO and COM terminals. Order does not matter.
  * LED pins should go to the light terminals. If the button does not light, unplug the LED and plug it in the opposite direction.
* Encoder pins will be marked as Data.
  * If the knob / turntable spins the opposite direction as intended and software reversing is not possible, swap the Data pins.
* All connectors are JST XH, unless otherwise noted.

## Gamo2 / arcin

### Phoenixwan+ and Faucetwo

#### Button Pins

<img src="../img/pwan-f2-button-pinout.png" width="400" />

#### Encoder Pins

Both 3 pin and 4 pin encoders are supported.

##### 4 Pin

<img src="../img/pwan-f2-encoder-4p-pinout.png" width="400" />

##### 3 Pin

<img src="../img/pwan-f2-encoder-3p-pinout.png" width="400" />

#### RGB

Both ARGB (WS2812b) and standard RGB (common-anode) have headers. 

##### ARGB

<img src="../img/pwan-f2-argb-pinout.png" width="400" />

##### RGB

<img src="../img/pwan-f2-rgb-pinout.png" width="400" />

#### USB and Power

<img src="../img/pwan-f2-usb-pinout.png" width="400" />

#### Analog

<img src="../img/pwan-f2-analog-pinout.png" width="400" />

### Older Controllers

#### Button Pins

<img src="../img/gamo2-arcin-button-pinout.png" width="400" />

#### Encoder Pins

Gamo2 has several types of boards. Ensure you are referencing the correct image.

##### IIDX (FPS / FP7 from 2014 on) / arcin (v1.1.1)

<img src="../img/gamo2-arcin-encoder-pinout.png" width="400" />

{: .note}
Analog mode is **only** possible with an arcin board.

## Yuancon / Roxy

### Button Pins

<img src="../img/yuancon-roxy-button-pinout.png" width="400" />

### Encoder Pins

<img src="../img/yuancon-roxy-encoder-pinout.png" width="400" />

{: .note}
* Analog mode is **only** possible with a Roxy board.
* Yuancon **only** supplies 5V. Roxy supplies 3.3V by default, with an optional solder jumper for 5V.

### RGB Pins

<img src="../img/yuancon-roxy-rgb-pinout.png" width="400" />

{: .note}
These RGB ports only support *common-anode* LEDs.