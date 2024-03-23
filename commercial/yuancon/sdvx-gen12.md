---
layout: default
title: YuanCon SDVX Gen12
parent: YuanCon
grand_parent: Commercial Controllers
nav_order: 2
---

# YuanCon SDVX Gen12

The Yuancon SDVX Gen 12 was first sold internationally in June 2021. It is notable for having a Turbocharger-like LED strip between the knobs, along with 2 RGB strips on either side of the controller.

## LEDs

As with the last few generations, this controller comes stock with bare LEDs in each button, as opposed to the industry standard of including the LED and current limiting resistor within the bulb. Beware using another board with this controller, as you **will** burn the LEDs out without supplying your own resistor.

This controller has 22 ohm resistors on-board instead. A short table of currents follows: 

| **LED**                         | **Current** |
|---------------------------------|:-----------:|
| Yuancon Stock LED (Blue)        | 35 mA       |
| Yuancon Stock LED (Pink)        | 32 mA       |
| Dao LED (Red)                   | 23 mA       |
| Comet Pinball 2SMD (Cool White) | 4 mA        |
| ISTMALL (White)                 | 3 mA        |

A typical current draw is around 20mA. This means that the stock LEDs **will** burn out from being run too high, and more conventional arcade LEDs will appear very dim. To save your LEDs from burning out, wire an 180 ohm or 200 ohm resistor in series with each LED.

It is unknown at this time whether Yuancon is aware of these issues. 