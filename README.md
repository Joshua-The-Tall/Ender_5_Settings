# Ender_5_Settings
Settings that should be used for the Ender5+ for optimal functionality, as well as general info.

----------------------------------------
# !!! IMPORTANT !!!
# Download the newest config bundle and import it via PrusaSlicer  
Then scroll down and select...  

-Print Settings: "0.2mm (0.4noz) Stable Speed"            (unless you have a different nozzle)
-Filaments: "Generic PLA+ Stable"                         (unless you're printing with PETG, or another filament)  
-Printers: "Creality Ender-5 Plus - StableKlipper 0.4Noz"
    -Note: This are overall settings for the printer. This should be the default selection.
        -Unless you are using exotic (Nylon, ASA, PA6-CF, etc) filament that the "Filament Overrides" section
        isn't capable of dealing with. As such, do not change anything here when switching filaments, just use
        the "Filaments overrides" in the filaments section

-Note: Anything marked "Stable" is an up-to-date version of the settings I've found to produce the best results,
at an acceptable speed. The printer is capable of faster, and cleaner results but usually sacrifices one for the other.
-----------------------------------------

# Current Modifications from the stock Ender 5 Plus design:

-Upgraded with the "volcano" (v6) nozzle from E3D (Used for higher speeds)  
-!!OLD!! Flashed Firmware to Marlin 2  
    -Firmware is still Marlin 2, however the machine is now being controlled via Klipper
    -Worst case scenario, if Klipper can't be used, Creality has the stock firmware on their website.
-Controlled via Klipperscreen, the touchscreen currently attached to the frame and the Raspberry Pi 4b underneath it.  
-Belt Tensioner on the X and Y-axis 
-Dual Gear Extruder motor 

If you have any further questions, let me know, or check the little pamphlet I made for our printer.
