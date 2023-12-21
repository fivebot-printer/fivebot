# fivebot Display Mount

![overview](assets/images/display/display-mount.png)

* Mounts to the front of the frame (or side, in case you use your printer rotated 90 deg with the dual z mod)
* No grounding issues like the stock mount, causing sporiadic button clicks
* Looks (subjectively) nicer
* Main restriction on placement is the display cable, will look into spec for a longer one
* Will be tweaked in the future to accomodate a panel if the printer is enclosed


## Bill of materials
|Quantity|Item|Comments|
|---|---|---|
|4|M3 screws|10 and 12 mm screws will work|
|2-4|M4 screws|10 mm|
|2-4|M4 T-nuts||

## Printed parts
Print the parts in the [STLs directory](https://github.com/fivebot-printer/fivebot/tree/main/display/STLs), quantity per naming convention `[name]_[quantity].stl`.

Print settings:
* Filament: (almost) anything should work for this mod, ABS or ASA generally recommended
* 5 top and bottom layers @ 0.2 mm layer height
* Walls either 5 walls @ 0.4 mm line width or 4 walls @ 0.6 line width
* 40% infill (or more)

## Installation
1. Power down the printer
2. Disconnect the stock display and disassemble from the stock mount
3. Mount the left and right brackets to the frame with M4 screws and T-nuts, use the front mount for reference on spacing
4. Insert the diplay PCB into the front panel and secure to the brackets with M3 screws
5. Move the electronics enclosure if you need to for the cable to reach the display connector (leftmost) port
6. Done!
