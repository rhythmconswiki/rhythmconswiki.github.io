---
layout: default
title: Electronics Basics
parent: Getting Started
nav_order: 3
---

# Electronics Basics
{: .no_toc}

This page covers a few basic concepts of electricity and electronics. While it is by no means comprehensive, understanding these can help you avoid damaging components. 


## Contents
{: .no_toc .text-delta }

- TOC
{:toc}

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

## Electronics Basics

This section reviews a few topics that are commonly used for controllers. 

### Logic Level

**Logic Level** refers to the voltage at which the microcontroller operates at. For Arduino boards based on the ATmega328 or 32U4, this is 5V. For most ARM-based boards (Raspberry Pi Pico, Teensy, Arduino SAM, arcin, Roxy), this is 3.3V. 

### Digital vs Analog

**Digital** is used to refer to a voltage measurement that takes the form of *two binary states*, typically referred to as **HIGH** and **LOW**. In a simple Arduino circuit, HIGH refers to a voltage of 5V and LOW refers to a voltage of 0V. In reality, there is a cut-off section. For a 5V circuit, approximately 3.0V or higher will equate to HIGH, and 1.5V or lower will equate to a LOW. The range between is not defined and should be avoided when using Digital logic.

In contrast, **Analog** is used to refer to a voltage measurement which can be *a range of values*. In simple Arduino circuits, this is usually a range of 0V to 5V. Most commonly, analog voltages are read into microcontrollers through an Analog-to-Digital Converter (ADC). This translates the volage to an equivalent integer. In most 5V Arduino platforms, this value can range from 0 to 1023, with 0 = 0V and 1023 = 5V. 

### Pull-up and Pull-down Resistors

As stated in the previous section, Digital signaling works best when signals are either at 0V or the logic level of the microcontroller. As a result, it is always a good idea to use **pull-up** or **pull-down resistors** to ensure that the voltage is either 0V or logic level. Typically, such resistors are 10K ohm but can be higher depending on the *strength* of the pull required. In addition, many microcontrollers have **internal pull-ups** which perform this function without any external resistors. They can be enabled or disabled via code and are generally recommended for switches and encoders. 