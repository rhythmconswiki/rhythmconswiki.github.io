---
layout: default
title: Encoders
parent: Parts
nav_order: 5
has_children: true
---

# Encoders
{: .no_toc }

This page lists options for **Incremental Encoders**, commonly used in DIY builds for [beatmania IIDX]({% link controllers/beatmania-iidx/beatmania-iidx.md %}) and [Sound Voltex]({% link controllers/sound-voltex/sound-voltex.md %}).

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Omron-style Clones (aka "Generic Chinese Encoder")

This style of encoder is durable and easy to mount and mount to. YuanCon controllers use a custom variant.

In most cases, one should select the options for **5-24V**, **NPN or Open Drain**, and **360 PPR**. Many guides suggest 600 PPR, but this is now considered to be far too fine resolution for the needs of a controller.

<img src="../img/generic-chinese-encoder.png" width="300" />

These can be found on Aliexpress and other storefronts by searching "Incremental Rotary Encoder".

The downside is that these encoders are extremely free-spinning, which requires external damping such as felt or an O-ring.

{: .note}
These encoders may not work with 3.3V power. It is recommended to power them on 5V, even if using a 3.3V microcontroller. Due to how the NPN logic works, it cannot output voltage on the output pins and poses no risk of damage.

### Mounting

Particularly on Sound Voltex controllers, typical construction consists of a base material with an acrylic plate on top for aesthetics. The encoder can either be mounted to the bottom or top material, with their own upsides and downsides.

When mounting the encoder, ensure the layer you're mounting to is not too thin or too thick. 3-5mm thickness is a good target range. Thinner materials run the risk of snapping, while thicker materials will lower the shaft to below usable levels.

#### Top Mounted

When top mounting the encoder, the bottom layer must have a large enough hole for the encoder body to pass through.

{% include image.html url="../img/encoder-top-mount.png" description="Cross section for top mounted encoder. Red indicates the top layer, and teal indicates the bottom layer." %}

#### Bottom Mounted

When bottom mounting the encoder, the top layer must have a large enough hole for the knob to pass through. This configuration runs the risk of lowering the knob below arcade spec, which may cause issues when switching between home play and arcade play.

{% include image.html url="../img/encoder-bottom-mount.png" description="Cross section for bottom mounted encoder. Red indicates the top layer, and teal indicates the bottom layer." %}

## Copal RES20D-50-201-1

This style of encoder was popularized by the DJ Dao SVRE5 and Virgoo Turbocharger. Generally, it's not recommended to use this in a new build as they're regarded as fragile.

<img src="../img/copal_res20d-50-201-1.png" width="300" />