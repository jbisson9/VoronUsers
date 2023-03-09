# Ultimate Z Chain Routing System for CAN bus

This is alternative wiring management solution to current methods.  And it was fun to design :)  The idea was to terminate cable within the channel with microfit connectors for easy maintenance.  Guides are used underneath to secure the wiring.  An optional screw and heat set insert are used to secure the system in place if needed.  Currently designed for V2.4 350mm.  CAD will need modification to work with other size and types of printers.

<img src="Images/Main_design.png" width="400px" />
<img src="Images/complete_system.jpg" width="400px" />

Note microfit connectors are pressure fit with specials retention jigs.

<img src="Images/Guides_and_Pressure_fit_connections.png" width="400px" />
<img src="Images/view_from_fan.jpg" width="400px" />

The BTT smart filament sensor fits into the printed part.  This is a remix from an unknown design listed on teamfdm.com (thanks!)

<img src="Images/view_from_BTT.jpg" width="400px" />

The system makes use of the keystone skirt, normally for USB/Rasp Pi connections, but in this case two microfit connectors are pressure fit into the slots

<img src="Images/view_from_base.jpg" width="400px" />

# Bill of Materials
* 2x M3 x 12 SHCS
* 2x M3 heat set insert
* 3x M3 x 8 BHCS
* 3x M3 Hammerhead T-Nuts
* 1x M5 x 10 SHCS
* 1x M5 Hammerhead T-Nuts
* 1x 2-circuit microfit 3 connector
* 2x 4-circuit microfit 3 connector
* tiewrap and heatshrink tubing

Tools:

  1.5mm Drill (optional)
Multimeter to check for Continuity
Super Glue
Soldering Iron for the heat inserts
Probe BOM:

1x microswitch (the omron D2F-5 or D2F-5L (removing the lever) is recommended), D2F-1 and similar sizes microswitch also work
2x M2x10 mm self tapping


# Printing

Print what you need.  Uses standard Voron print profiles.  Supports not needed but in reality the BTT top channel part could use it (sorry first design and I don't have all my sh*^Y#t together)

# Assembly

Attach the BTT sensor to the top channel piece with two M3 button head screws.  Create the wiring harnesses to attach the microfit connectors.  As an aside, all three ends are males connectors, unusual generally, but easier to build clam shells around them.  

<img src="Images/microfit_clam_shell.jpg" width="400px" />

Once the harness is built up, add the microfit clam shells and insert them into the channels.  They are pressure fit and tight.

<img src="Images/completed_assy.jpg" width="400px" />

Finished cabling should look like this.  Be sure to slide in the cable guide on the unit before attaching it to the frame.

<img src="Images/example_cabling.jpg" width="400px" />

Secure the entire unit to the frame with four M3x12 SHCS and T-Nuts.

# Optional

If you want to secure the entire system to the panel, use a heat set insert and backer.  The panel is only 3mm thick so you'll need something to secure the rest. 

<img src="Images/Optional_Screw_with_heat_set_insert.png" width="400px" />

All the best!