---
layout: default
title: Electronics Basics
nav_order: 3
has_children: true
---

# Electronics Basics

This page covers a few basic concepts of electricity and electronics. While it is by no means comprehensive, understanding these can help you avoid damaging components. 

## Electricity Basics

Two key concepts to understand are:
1. Voltage
2. Current

### Voltage

Voltage (measured by unit Volts [V]) refers to the electric potential between two points, and as such, is a *relative* measurement. Commonly, we refer to **Ground (GND)** to be a point that we designate as **0V**.

Most commonly, voltage is encountered through batteries, DC chargers, or other power supplies. While this is an oversimplification, it is an easy rule of thumb that using *a higher voltage than what is expected* will damage components. However, using *a lower voltage than what is expected* will, in most circumstances, not be harmful. However, a component using a lower voltage may not operate correctly. 

### Current

Current (measured by the unit Ampere or Amp [A]) refers to the amount of electrical flow per a given time. This measurement is taken *in line* with a wire.

Most commonly, current is encountered to represent a *maximum* amount that a DC charger or power supply can give to a circuit. For example, a common threshold to keep in mind is the limit of USB 2.0, which is 0.5A or 500mA. If this limit is exceeded, it can cause issues for the power supply and may result in damage.

In general, excessive current *can damage components*. While some components can regulate current themselves, other components (such as LEDs) will need what is called a **current limiting resistor**. See the page on [Wiring LEDs](./wiring-leds.md) for more information. 