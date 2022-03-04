# Eagle-ULPs
This repository contains some useful, ULPs that I have written myself or just enhanced.

Eagle is a schematic capture and PCB layout program.
ULPs are user written programs which automate some useful tasks.

a_place.ulp
  This program is to be used after a schematic has been completed and a new board created. By default all of the parts are placed off-board and grouped by part type. 
This isn't too useful. Normally moving parts to initial desired PCB locations requires a lot of zooming in and out. 

Typically you want the parts that are close together in the schematic to be close together on the PCB (shorter traces, fewer vias). 

This ULP moves all parts in the selected schematic sheet to the same relative positions on the PCB. You can scale the target area to be less than the whole PCB and select which schematic sheet you want to map.

Parts still have to be rotated and moved afterwards but this really removes a lot of effort normally expended for initial part placement.
