# Artillery Sidewinder X1 Klipper Config
klipper config file for Artillery Sidewinder X1+BLTouch+E3D Hemera.
The modification to my printer are per below.
- Change all V-Rollers to PC rollers.
- Added Z Brace kit from Creality CR-10 Kit.
- Remove Z sync belt
- Change Z nut to POM
- Flexplate
- Bed cable relief+cable chain
- Nylock nuts on bed
- BLTouch 3.1
- E3D Hemera + Nozzle X
- Change extruder stepper to LV8729 1/64 microstepping
- Hemera V6 Part Cooling Duct & Mount https://www.thingiverse.com/thing:4042492
- hemera mount with BLtouch https://www.thingiverse.com/thing:4856807
- 3 Screw Hemera Duct Mount Plate https://www.thingiverse.com/thing:4260308
- Klipper Screen
- Change Solid State Relay to OMRON G3NA-210B DC5-24V

I've mix and match Klipper configs from multiple sources and some of my own.
- https://github.com/Clank50AE/Clanks-Klipper-Configs
- https://github.com/ascii-ts/my-klipper-configs#readme
- https://github.com/JJShankles/3d-printers
- https://gist.github.com/ChipCE/95fdbd3c2f3a064397f9610f915f7d02

and many other config that I have saved tidbits and try swapping them around until my printer moved. Some more adjusting still needed so please expect to tinker around with it.

Please feelfree to use,but the most important message of all keep in mind I don't know WTF i'm doing. risk is your own lol.
Keep your power switch close.


Worth reading refs
- Print tuning guide https://github.com/AndrewEllis93/Print-Tuning-Guide
- Klipper Gcode https://www.klipper3d.org/G-Codes
- Z offset calribrate https://www.klipper3d.org/Probe_Calibrate.html
- Linear Advanced/ Pressure Advanced https://www.klipper3d.org/Pressure_Advance.html
- Input shaper https://www.klipper3d.org/Measuring_Resonances.html
- Maxing out the speed https://www.klipper3d.org/Resonance_Compensation.html#tuning
- SET_PRESSURE_ADVANCE ADVANCE=0
- SET_VELOCITY_LIMIT ACCEL_TO_DECEL=7000
- TUNING_TOWER command=set_velocity_limit parameter=accel start=1250 factor=100 band=5
- Selectging the max speed https://www.klipper3d.org/Resonance_Compensation.html#selecting-max_accel
- Klipper mesh on print area only install guide https://gist.github.com/ChipCE/95fdbd3c2f3a064397f9610f915f7d02#klipper-mesh-on-print-area-only-install-guide

Worth watching refs

- Klipper Initial Setup : Making sure things are all good before printing https://youtu.be/T-knWbh1Gg8
- Klipper guide: Input shaping, pressure advance and macros (manual + accelerometer) https://youtu.be/EJapxNsntsQ
- INPUT SHAPER CRASH COURSE - Print FASTER and BETTER! https://youtu.be/OoWQUcFimX8
- Klipper input shaping - A leap forward in high speed AND high quality 3D printing [Rat Rig part 4] https://youtu.be/er7q-CJL1lc?t=713
- MAX OUT ACCELERATION - Find your printers limit with input shaper! https://youtu.be/IezqWVZZ_iI
