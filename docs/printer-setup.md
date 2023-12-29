---
title: Printer setup
nav_order: 2
---
# fivebot printer setup guide

While one of the overall goals is to keep everything modular and play nice with other mods, there is some general thinking and recommendations for the printer setup that will be covered here. Hopefully to provide some good reference points and guidance.

## Recommended hardware

### Main control board
Stock board config will be provided, with a strong recommendation to upgrade to a board with 5 independent stepper *drivers*. Main suggestions are BTT SKR 3 and BTT Octopus 1.1, preferably purchased in a bundle with 5 or more TMC2209 drivers. Configuration will be provided for both of these boards.

### Probe
It is highly recommended to install a probe to enable auto bed tilt adjustment with the dual Z mod. Which probes are available depends on toolhead/shroud implemented. If you have the stock toolhead a CR Touch or BL Touch is the simplest way too start.

## Klipper

{: .highlight }
Section to be updated with more details and links.

The [Klipper firmware](https://www.klipper3d.org/) will be central to the printer setup and mods.

* Installation - [use KIAUH](https://github.com/dw-0/kiauh) and follow guides
  * Stock board
  * SKR 3
  * Octopus 1.1
* Base configuration
  * Stock board
  * SKR 3
  * Octopus 1.1
