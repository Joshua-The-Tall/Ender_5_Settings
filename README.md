# Ender_5_Settings
Settings that should be used for the Ender5+ for optimal functionality, as well as general info.

----------------------------------------
# !!! IMPORTANT !!!
# Download the newest config bundle and import it via PrusaSlicer, to use the best settings
-----------------------------------------

# Current Modifications from the stock design:
-Upgraded with the "volcano" (v6) nozzle from E3D (Used for higher speeds)  
-!!OLD!! Flashed Firmware to Marlin 2  
-Firmware is still Marlin 2, however the machine is now being controlled via Klipper  
  -This is controlled via Klipperscreen, the touchscreen currently attached to the frame and the Raspberry Pi 4b underneath it.  
-Belt Tensioner on the X-axis  
-Dual Gear Extruder motor  




# Old Instructions Below----

**----To use the Gcode----**

-If you have already added the ender 5+ machine, skip the first paragraph!

-If you do not have the ender5+ already added, look back and instead click "add new" in the top right. Non-Ultimaker Printer. "Add a non-Networked Printer".
Close the ultimaker dropdown, and open the creality3d one, Then select "Ender-5 Plus". From there, repeat continue in the previous paragraph

Open Cura. Settings in top left. Dropdown to "Manage Printers".
Printers. Machine Settings. Copy/Paste the first half into the box labeled "Start G-code", making sure to replace all text that existed before.
Copy/Paste the second half (under the bar labeled End G-code) into the "End G-code". Close, and proceed with normal operation

**----To use the Filament Profile----**
 
Under the top right drop down menu, under profile "Manage Profiles", Then import the file.
