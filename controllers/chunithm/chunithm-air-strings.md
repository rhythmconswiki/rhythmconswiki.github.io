---
layout: default
title: Chunithm Air Strings
description: General info on the Sega Chunithm Air Strings.
parent: Chunithm
grand_parent: Controllers
nav_order: 2
---

# Chunithm Ground Slider
{: .no_toc }

This page lists details related to the official Chunithm Air Strings, taken off an arcade cabinet.

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Sensors

The IR transmitters and receivers are Shinkoh Electronics P/N KB893, which have been discontinued.

## Pinouts

The outputs are split between the two towers, so each has 3. Starting from the lowermost beam to the uppermost beam, the order is as follows: 
* Pin 8, right tower
* Pin 8, left tower
* Pin 9, right tower
* Pin 9, left tower
* Pin 10, right tower
* Pin 10, left tower

Note pin numbering is right to left, so pin 8 is the central pin of row 2, pin 10 the leftmost pin of row 2, and pin 9 is between them. 

{% include image.html url="../img/chunithm-air-string-sensor-connector.jpg" description="An image showing the sensor connector from a chunithm air string unit. The pinout is annotated, left to right, top to bottom, as so: 5V, TOWER, TOWER, TOWER, TOWER, TOWER, TOWER, OUTPUT, OUTPUT, OUTPUT, GND, GND, NC, EARTH. The pins marked 'tower' connect to the other air tower on the other side, so pin 2 -> pin 2, pin 3 -> pin 3 and so on. Outputs are where the state of the tower can be read from (order to be checked)." %}

{% include image.html url="../img/chunithm-air-string-led-connector.jpg" description="An image showing the LED connector from a chunithm air string unit. The pinout is annotated, left to right, top to bottom, as so: NC, NC, GND, 12V, NC, DI." %}

## Using on a PC

To interface the Air Strings with your PC, consider the following board: [https://github.com/Lemony0301/pcb-for-AIR_STRING](https://github.com/Lemony0301/pcb-for-AIR_STRING)

## LED Strip

The LED strip is a 48 LED/meter 12V WS2811 strip.
