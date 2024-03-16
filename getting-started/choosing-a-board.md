---
layout: default
title: Choosing a Board
parent: Getting Started
nav_order: 5
---

# Choosing a Board
{: .no_toc }

Choosing a board is an important part of creating your controller! There are many options for the DIY enthusiast, so let's take a look. 

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Summary

If you're short on time and looking for the cheapest option, get an **Arduino Leonardo**, **Arduino Micro**, or a **Sparkfun Pro Micro** (or the equivalent clone board). These boards provide native USB support and have plenty of pins to build a wide variety of controllers.

It is ***not recommended*** to use an Arduino Uno, Arduino Nano, or Arduino Mega. These boards do not have native USB support. While software USB an option, it is significantly slower and will result in latency.

In the most basic configuration, you will need **one pin per button**, **one pin per LED**, and **two pins per encoder**. This allows for the most straight forward method of wiring and the simplest to program. 

### Encoders

This page assumes you are using Quadrature Encoders, such as generic Chinese Rotary Encoders, Copals, Bourns, or other two pin encoders. If you are using a potentiometer, such as the Sensatec ELV-24Y36A-K or other generic pot, these instructions will not apply. Those will need a single analog pin, which many boards support without issue.

Quadrature Encoders are most responsive when they are used on interrupt-capable pins. This page will assume you will wire the encoder to interrupt pins. It is possible to use other pins for encoders at the risk of latency. See specific controller pages for information on controllers using more than 2 encoders. 

## Arduino (ATmega32U4)

### Leonardo

The Leonardo can support one of the following setups:

* 10 Buttons and 10 LEDs
* 9 Buttons, 9 LEDs, and 1 Encoder
* 8 Buttons, 8 LEDs, and 2 Encoders

3 more pins are accessible using non-standard methods, and 1 additional pin is accessible by modifying the core files. 

### Micro

The Micro can support one of the following setups:

* 11 Buttons and 11 LEDs
* 10 Buttons, 10 LEDs, and 1 Encoder
* 9 Buttons, 9 LEDs, and 2 Encoders

1 additional pin is available, and 1 additional pin is accessible by modifying the core files. 

### Pro Micro

The Pro Micro can support one of the following setups:

* 9 Buttons and 9 LEDs
* 8 Buttons, 8 LEDs, and 1 Encoder
* 7 Buttons, 7 LEDs, and 2 Encoders

## Raspberry Pi

### Pi Pico

The Pi Pico has 26 GPIO pins with 3 of them being ADC capable and features a dual-core cortex M0+ at up to 133MHz. It is fairly inexpensive and can support C/C++ or MicroPython. Since it's release, several codebases have been developed, making this another good option. Can theoretically support:

* 13 Buttons and 13 LEDs
* 12 Buttons, 12 LEDs, and 1 Encoder
* 11 Buttons, 11 LEDs, and 2 Encoders

## Teensy

The Teensy series, designed by PJRC, are a popular series of microcontroller boards. 

Currently, only the Teensy 4.X series are available for stock, which are not recommended for controller usage by beginners due to their custom USB stack and high price.

## Community Options

There are two community-developed options that were previously available for purchase. They are not currently, but are available on the second-hand market.

### arcin

The arcin is an open-source project designed as a drop-in replacement for DJ Dao / Gamo2 controllers. Features:

* 11 Buttons / LEDs
* 2 Quadrature Encoders or Analog Potentiometers
* 2 Generic LED outputs
* WS2812b support on Button 9 (cannot use Button 9 if enabled)
* Headers for PS2 support

### Roxy

The Roxy is a fork of the arcin designed as a drop-in replacement for Yuancon controllers. Features:

* 12 Buttons / LEDs
* 2 Quadrature Encoders or Analog Potentiometers
* 1 Generic LED output
* Built-in driver for up to 4 RGB common-anode LEDs
* WS2812b support (disables on-board LED driver)
* Headers for PS2 support

## Other Options

It is not recommended to use a fightstick board, such as products from Brook or the generic "zero delay encoder" boards you find on Amazon or eBay, as these do not have inputs for encoders or connectors for LEDs. 