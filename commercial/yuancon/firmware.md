---
layout: default
title: YuanCon Firmware
parent: YuanCon
grand_parent: Commercial Controllers
nav_order: 1
redirect_from:
  - /w/YuanCon_Firmware
---

# YuanCon Firmware
{: .no_toc }

This page contains instructions and links for how to update the firmware for YuanCon controllers.

Contents
{: .no_toc .text-delta }

- TOC
{:toc}

{: .note}
Some updater excecutables are unsigned and therefore may be flagged as malware. This is a false positive.

## Sound Voltex

### SDVX Gen12

For SDVX Gen12 controllers, the firmware update file is embedded within the updater.

1. Download the latest firmware below
2. Plug in your SDVX Gen12 controller
3. Press 'Enter' and it will start updating

#### Versions

**v1.11 (Latest)** - [Download](https://archive.org/download/yuan-con-sdvx-12-v1.11-updater/YuanCon_SDVX_12_v1.11_updater.zip)
> Fixes the top RGB strip going in opposite direction of the knobs

**v1.10 Beta** - [Download](https://archive.org/download/yuan-con-sdvx-12-v1.10beta-updater/YuanCon_SDVX_12_v1.10beta_updater.zip)
> Fixes compatibility with EAC/Konasute

**v1.04** - [Download](https://archive.org/download/yuan-con-sdvx-12-v1.04-updater/YuanCon_SDVX_12_v1.04_updater.zip)
> This version has no known changes or fixes from the previous version.

**v1.03** - [Download](https://archive.org/download/yuan-con-sdvx-12-v1.03-updater/YuanCon_SDVX_12_v1.03_updater.zip)
> This version has no known changes or fixes from the previous version.

### SDVX Lite 3

For SDVX Lite 3 controllers, the firmware update file is embedded within the updater.

1. Download the latest firmware below
2. Plug in your SDVX Lite 3 controller
3. Press 'Enter' and it will start updating

#### Versions

**v3.1 (Latest)** - [Download](https://archive.org/download/yuan-con-sdvx-lite-3-v3.1-updater/YuanCon_SDVX_Lite3_v3.1_updater.zip)
> TODO: Changes (currently unknown)

### Older Controllers

For controllers prior to SDVX Gen12, and SDVX Lite (1, 2/+), the firmware file and update utility are separate.

1. Download the old [YuanCon Update](https://archive.org/download/yuan-con-old-firmware-updater-dzpw/YuanCon_old_firmware_updater.zip) utility
2. Download the desired firmware version below
3. Plug in your controller and put it into update mode (see: [What are the different modes for YuanCon SDVX controllers?](https://rhythm-cons.wiki/w/YuanCon_FAQ#What_are_the_different_modes_for_YuanCon_SDVX_controllers?))
4. Start the YuanCon Update utility and select downloaded firmware file
5. Press "Start Upgrade" and wait until the updater is finished

#### Versions

**2021-12-05 (Latest)** - [Download for Standard Model](https://archive.org/download/yuan-con-sdvx-old-211205v-3/YuanCon_SDVX_old_211205v3.bf) - [Download for Lite Model](https://archive.org/download/yuan-con-sdvx-lite-211205v-3/YuanCon_SDVX_Lite_211205v3.bf)
> Fixes EAC compatibility for Lite controllers
> Fixes knob behavior and adds EAC compatibility for Standard model controllers
> This update changes the behavior of modes and adds lighting control capabilities, [see here](https://twitter.com/ahyuan0312/status/1467494109216755714) for the new behaviors (TODO: consolidate info into wiki)

**2020-04-03** - [Download for Standard Model](https://archive.org/download/yuan-con-sdvx-old-200403/YuanCon_SDVX_old_200403.bf)
> The infamous knob behavior update that disables RGB lights, and only has the corrected behavior in mode 1

**Original (RGB)** - [Download for Standard Model](https://archive.org/download/yuan-con-sdvx-old-original/YuanCon_SDVX_old_original.bf)
> The original firmware for old RGB YuanCon controllers, use on non-RGB controllers at your own risk
> Has inaccurate constant-speed knob behavior (see [here](https://rhythm-cons.wiki/w/Yuan_FAQ#The_knobs_on_my_older_controller_aren't_behaving_right,_how_do_I_fix_it?))

## beatmania IIDX

### Dx5th

For Dx5th controllers, the firmware update file is embedded within the updater.

1. Download the latest firmware below
2. Plug in your Dx5th controller
3. Press 'Enter' and it will start updating

#### Versions

**v2.5 (Latest)** - [Download](https://archive.org/download/yuan-con-iidx-dx-5th-v-2.5/YuanCon_IIDX_Dx5th_v2.5.zip)
> Changelog TODO
> [Video Manual](https://www.youtube.com/watch?v=hpwj2_w_wZQ)

**v1.5 Beta** - [Download](https://archive.org/download/yuan-con-iidx-dx-5th-v1.5/YuanCon_IIDX_Dx5th_v1.5.zip)
> Adds RGB light adjustment, see [here](https://twitter.com/ahyuan0312/status/1510560637608349700) for full reference

**v1.1** - [Download](https://archive.org/download/yuan-con-iidx-dx-5th-v1.1/YuanCon_IIDX_Dx5th_v1.1.zip)
> Fixes compatibility with Infinitas

### Older Controllers

For controllers prior to the Dx5th, the firmware update file and utility are separate.

1. Download the old [YuanCon Update](https://archive.org/download/yuan-con-old-firmware-updater-dzpw/YuanCon_old_firmware_updater.zip) utility
2. Download the desired firmware version below
3. Hold Start + Select + V.E.F.X and plug in your controller
4. Start the YuanCon Update utility and select downloaded firmware file
5. Press "Start Upgrade" and wait until the updater is finished

#### Versions

**2022-06-26 (Latest)** - [Download](https://archive.org/download/yuan-con-iidx-old-220626v2/YuanCon_IIDX_old_220626v2.bf)
> Adds Infinitas support for old controllers and makes the turntable more sensitive, lighting is still broken.

**2020-03-12** - [Download](https://archive.org/download/yuan-con-iidx-old-200312/YuanCon_IIDX_old_200312.bf)
> Breaks lighting on all modes except mode 1