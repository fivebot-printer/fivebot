---
title: Home
nav_order: 1
---
# The fivebot 3D printer

![fivebot-printer](assets/images/fivebot-printer.png)

The goal of the fivebot 3D printer project is to develop a set of, ideally modular, upgrades for the Creality Ender 5 and Ender 5 Pro printers, and if possible also the Ender 5 Plus. Hopefully, making it an affordable, relatively fast, and reliable printer that can stay relevant in the rapidly developing 3D printer market. 

The intention is in no way to compete with the already existing and awesome [Zero G](https://zerog.one/) mods, but to provide a distinctly different alternative with the following goals and constraints in mind:

* Keep it as cheap/affordable as reasonable
* Use as much stock parts as possible, and add matching hardware
* No modification of the frame
* Make the printer easy to enclose
* Strive to keep it accessible for less experienced modders, minimize use of heat inserts, soldering etc or provide alternative routes
* Provided with Klipper firmware configuration primarily (contributions for other firmares welcome of course)

## Avilable mods

| Mod | Description | Status |
| :--- | :--- | :--- |
| [Dual Z](dual-z.html) | Dual lead screws and motors for the Z axis. | **beta**{: .label .label-purple} |
| [Thrust bearing stepper bracket](dual-z.html#stepper-motor-brackets)  |  Offload axial load on the Z stepper shaft(s) to potentially reduce Z-axis banding/artifacts | **beta**{: .label .label-purple} |
| [Display mount](display.html)  | Better looks and no grounding issues | **beta**{: .label .label-purple} |

List of planned modifications, roughly in order of priority:

* Core-XY using stock roller wheels (lots of core-xy mods with rails already exist)
* X-gantry adapters for other existing toolheads (thinking Voron, XOL, complicated mods)
* Lightweight integrated toolhead for the stock hotend (easy mod)

And future ideas and improvements:
* Dual Z add-on motor sync belt, when used with a single stepper driver
* Electronics comparment with more space for a bigger board and Pi
* Belt-driven dual Z with a single motor
* Touch screen mount/support
* Affordable triple-z setup with linear rods and stock bed

## Supporting the project
A couple of things you can do to support:
* Install the mods and share your feedback in the discord or as a [GitHub issue](https://github.com/fivebot-printer/fivebot/issues)
* Submit documentations improvements, firmware configs or additional mods, ideally as a [pull-request](https://github.com/fivebot-printer/fivebot/pulls)
* [Buy me a coffee](https://www.paypal.com/donate/?hosted_button_id=UQVMLLJJ374PJ) (or filament/hardware for development purposes!)

## General instructions

{: .warning }
Any modification of your 3D printer is done at your own risk and this project comes without warranties! Take special care and attention when dealing with anyhing electricity. Read the instructions carefully before getting started and apply common sense.

### Assembly
When assembling plastic parts, remember not to over-tighten and to come back to check and re-tighten if necessary (since all plastics will creep to varying degrees).

### Printed parts
Files in each mod's STLs directory, linked from each page. Required quantity per naming convention `[name]_[quantity].stl`. Any alternatives or optional parts are specified per mod.

STLs should be oriented correctly for printing.

**Print settings:**
* Filament: ABS or ASA preferrably, if not possible then PETG, PLA not recommended unless stated otherwise (temperature and mechanical properties)
* 5 top and bottom layers @ 0.2 mm layer height
* Walls either 5 walls @ 0.4 mm line width or 4 walls @ 0.6 line width
* 40% infill (or more)
