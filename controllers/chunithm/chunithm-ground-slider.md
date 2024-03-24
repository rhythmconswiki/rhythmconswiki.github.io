---
layout: default
title: Chunithm Ground Slider
parent: Chunithm
grand_parent: Controllers
nav_order: 1
redirect_from:
  - /w/Chunithm_Ground_Slider
---

# Chunithm Ground Slider
{: .no_toc }

This page lists details related to the official Chunithm Ground Slider, taken off an arcade cabinet.

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Basics

The ground slider requires a 12v power supply and communicates via serial. You can hook it up to a PC using pins 2, 3 and 5 on an RS232 cable. Your RS232 cable should be configured to communicate on port COM1. Please be aware of the below diagram for how to connect the board via usb. 

## Cable Harness Connectors

The items below are to mate with the stock harness. Do not order them unless your slider came with the harness. 

### Power Connector

* YLR-03V Qty 1
* YLS-03V Qty 1
* SYM-01T-P0.5A Qty 3 (26-20 AWG) **OR** YM-41T-P0.5A Qty 3 (20-16 AWG)

### Serial Connector

* SMP-04V-NC Qty 1
* SHF-001T-0.8BS Qty 3 (28-22 AWG)

## Board Connectors

The items below are to mate with the PCB connectors. It is not necessary to buy these if you have the harness (unless you want to make your own harness). 

### Power Connector

* XAP-04V-1 Qty 1
* SXA-001T-P0.6 Qty 4 (28-22 AWG) **OR** SXA-01T-P0.6 Qty 4 (24-20 AWG)

### Serial Connector

* XAP-03V-1 Qty 1
* SXA-001T-P0.6 Qty 3 (28-22 AWG) **OR** SXA-01T-P0.6 Qty 3 (24-20 AWG)

{% include image.html url="../img/chunithm-serial-wiring.png" description="How to connect a slider to a PC over USB" %}

## Pinout

There are four connectors on the slider. The ones we are concerned with are the second from left, and the rightmost connectors. These are the serial and power ports, respectively. 

{% include image.html url="../img/chunithm-slider-back.jpg" description="Back of an arcade Chunithm slider, showing the four connectors." %}

{% include image.html url="../img/chunithm-slider-serial-connector.jpg" description="Image showing the two leftmost connectors on the chunithm arcade slider. The pinout of the right hand (serial) connector is annotated, left to right, as GND, TX, RX." %}

{% include image.html url="../img/chunithm-slider-power-connector.jpg" description="Image showing the rightmost connector on the chunithm arcade slider. The connector is annotated, top to bottom, with the pinouts of GND, GND, 12V, 12V." %}

### Extra Info

Most users will not need to access the programming port, but the pinout is listed below.

{% include image.html url="../img/chunithm-slider-issp-conector.png" description="Image labelling the pins on one of the chunithm slider's programming ports. From top to bottom, the pins are 5v, ground, reset, issp-sclk and issp-sdata." %}