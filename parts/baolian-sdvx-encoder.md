---
layout: default
title: Baolian SDVX Encoders
parent: Encoders
grand_parent: Parts
nav_order: 1
---

# Baolian SDVX Encoders
{: .no_toc }

The Chinese company Baolian sells a knob assembly that is designed to be a drop-in replacement for the official arcade assembly. It uses a hall effect sensor and a magnet mounted to the shaft to determine the angle.

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Outputs

This encoder features three different types of outputs.

### Analog

This output mimics the hall effect sensor used in the arcade cabinet, ranging from 0V to 3.3V through a full rotation. Included with the encoder is an adapter board that scales the output from 0V to 5V.

The connector is JST PH 3 pin.

{: .note}
The Sensatec potentiometer on the arcade cabinets use JST ZH, so an adapter cable is required.

This is the recommended output method.

### Pulse Output

This output sends one pulse at the set resolution, but it is **not** a quadrature output. One wire outputs pulses on a clockwise rotation, while the other wire outputs pulses on a counterclockwise rotation.

The connector is JST PH 6 pin.

{: .note}
This is an open-drain output, so pull-up resistors are required for the signal to return high.

{: .warning}
If spun too fast, there is no longer a separation between pulses. Effectively, this mode is like holding a button for the encoder instead of giving proper analog control. It is not recommended.

### Serial Output

The serial output has the following configuration:
- Baud Rate: 115200
- Date Bit: 8
- Parity Bit: None
- Stop Bit: 1

And will only send one of the two messages:
- Spin Right: 0xFF 0x00 0x00 0x01
- Spin Left: 0xFF 0x00 0x00 0xFE

The connector is JST PH 4 pin.

{: .note}
Due to the fairly high baud rate, hardware serial is likely required to capture signals correctly.

### Pinouts

See the following image for pinouts:

<img src="../img/baolian-sdvx-pinout.png" width="500" />

## DIP Switch Configuration

The DIP switches configure the resolution of the pulse and serial output. Per the datasheet:

| Switch 1 | Switch 2 | Pulses Per Rotation |
|:--------:|:--------:|:-------------------:|
| OFF      | OFF      | 16                  |
| ON       | OFF      | 64                  |
| OFF      | ON       | 512                 |
| ON       | ON       | 1024                |

The last switch configures the duration of the pulse output.

| Switch 3 | Pulse Length |
|:--------:|:------------:|
| ON       | 0.5ms        |
| OFF      | 8ms          |
