# Juicebox
Miniature IP5328P-based dual 18650 powerbank

Why buy a fire hazard when you can make one? 18650 cells are readily available and cheap (especially if you hate having insurance) and aliexpress is full of questionably designed driver boards.
Juicebox combines these two exhilarating ways of life into a handy miniature package the size of a small frag grenade

## Features
- injoinic IP5328P-based power board
	- 2x USB Type A outputs
	- 1x USB Type C input/output
	- 1x USB micro-B  input
	- 5/9/12v output
	- 5/9v input
	- Supports QC2/3, FCP, AFC, USB-PD etc.
	- Supports PPS adjustable voltage
	- Full IC datasheet [here](http://www.injoinic.com/wwwroot/uploads/files/20200221/ec29931791194a51119ee1d6a4a21efb.pdf)
- 2x Detachable 18650 cells in cradle for easy replacement
- Fire extinguisher not included (optional)

## Parts
This project consists of 4 printable components, available within the design f3d/step files, as well as STLs in [/Output/STL](/Output/STL):
- Midplate: 3mm thick plate used for attaching the controller board to the battery holder
- Case_Shell: Outer housing for the powerbank, print upright with supports
- Case_cover_L: left cap (looking at the port side) for screwing into the enclosure and battery holder, print it with the outer part facing up and use supports for the lip.
- Case_cover_R: Right cap incorporating a passthrough for the power button and a microUSB port hole, print like the left

#### Additional parts required:
- IP5328P charging board. Similar to [this](https://www.aliexpress.com/item/4000574214602.html) or just use it as a search term on AliExpress/Amazon.
- 2x 18650 cell battery holder. I used [this](https://grobotronics.com/battery-holder-2x18650-for-pcb.html) from a Greek shop and I don't know how common it is but dimensions are 80x42mm with a 19x55mm screw pattern for the bottom and 19mm apart side screws
- 8x M2.5x3 Philips thin-capped screws for the mounting midplate
- 6x M2.5x4 Philips thin-capped screws for the sides

## License
This design is licensed under the WTFPL because if you light your backpack on fire I want nothing to do with it.

Enjoy :)
