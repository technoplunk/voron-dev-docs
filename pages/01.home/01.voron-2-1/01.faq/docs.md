---
title: FAQ
date: '18:57 19-09-2019'
taxonomy:
    category:
        - docs
visible: true
---

# Voron FAQ
[TOC]

## General
### Should I build a Voron?
Yes


### Should I wait for version 2.2 ? 
Version 2.2 is being heavily tested as of May 2019 - you will be able to upgrade your 2.1.1 printer with the new printed parts later. There is no need to wait for 2.2.


### Will cad source files be released?
No planned date on the released of cad files, step files, or anything other than the stls

### What is the purpose of this server?
To help others build a voron, if you are not building a voron, the 3dp discord is a better place for you.

### How much does a Voron cost?
A 300^3 build will cost approximately $1,000 USD. The move from 300 to 350 is much more significant than 250 to 300.

### Can I scale the frame larger than 350^3?
Yes, but it will be more expensive, with a reduction in print quality, and much slower than the supported sizes. The machine was also never designed to support those sizes so you will run into structural issues. 

### Can I use these 4040 extrusions that I have from another project?
Yes, but be prepared to redesign nearly every part.

### Why does the Voron use only 2020 extrusions?
Because 2020 is enough for the application. It’s not a CNC machine and the strength to weight/stiffness ratio is more than ideal for 3DP where no side loads or cutting forces are imparted.

### Does the Voron Support the Super Volcano
There are no plans to support it until TL clones it

## Printing Voron parts
### How much material do I need?
 - Buy 2 Rolls of Primary and 1 Roll of Accent (1kg per roll) and you should be able to get most of the machine printed.
 - You will need less for a 1.6 machine
 - You may need more for a larger 2.1 machine, mostly because of the skirts

### What are the “official” colors of Voron?
 - Black eSun ABS+ or Paramount Black
 - Red: Hatchbox ABS or Paramount Enzo Red

### What are the recommended print settings for Voron parts?
* Settings
    * 0.2mm layer heightforce .4mm extrusion width, 40% infill, 4 perimeters, and 5 top/bottom layers.
    * The following parts should be 5 perimeters, 8 top and bottom layers and 50% infill: xy_topbrace_left, xy_topbrace_right, idler_frame_left_lower/upper, and idler_frame_right_lower/upper. These only appear on V2 Printers
    * Supports are not required.
    * Recommended Infill Pattern is Fast Honeycomb in S3D, other valid infill is as follows: Gyroid, Cubic, Grid and Triangle.
* Slicers
    * Tested Slicers are as follows: S3D, Slic3r Prusa Edition, Cura
    *  **We do not recommend using Pathio to slice your parts.**
*  Filament
    *  Approved filament is either ABS or ABS+.
    *  No, PETG will not work. Dont use polycarbonate or nylon either, machines have failed with these materials catastrophically.
    *  Filled filaments make your shit look awesome, but much more prone to layer separation, dont use them
    *  No annealed PLA, its too brittle and has absolutely shit tolerances after the annealing process.
    *  Standard PLA is only acceptable on items outside the chamber; ie: display housing, skirts, panel clips, handles.
    *  Do not print any of the motion system in anything but ABS.

### What if I cannot print ABS reliably?
ABS+ is easier to print without warping even if you can only use a cardboard enclosure. Alternatively you can submit a request in #pif-discussion. There is likely a lead time until delivery. Use this time to submit your AliExpress orders and wait.

### What are the recommended accent parts?
The recommended accent parts are denoted with an underscore (_) in the filename. Many of these are still functional in nature and should still follow the recommended print settings.

### Can you print voron parts using a volcano
VORON parts are designed with a 0.4mm nozzle in mind, it is not recommended to use a 0.4mm nozzle with a volcano, even though it is available

## Sourcing
[Official Sourcing Sheet](https://docs.google.com/spreadsheets/d/1QS80JOHcgBIABJrAD7sIsVr5nARIzHsFrJnI4P4npgs/)
* VORON 2 Dev Team - Sourcing Guide: See Tab 1
* VORON 1 Dev Team - Sourcing Guide: In Process - See Tab 2
* VORON Mobius 3 - Dev Team Sourcing Guide: See Tab 3
* VORON Recommended Tools - Dev Team Sourcing Guide: See Tab 4

### Where should I buy my parts from?
A large portion of parts come from AliExpress, Arrow, Mouser, Digikey and Misumi.

### What are the parts I should order from specific sources?  
 - Extrusions and Corner Cubes: Misumi
 - Linear Rails (for V2): CNA - Aliexpress Store
 - Linear Shafts and Bearings (for V1): Misumi
 - Pulleys and Closed Loops Belts: Powge - Aliexpress Store 
 - RAMPs Kits: Zyltec 
 - Hotends, BMG Gear Sets, Open Loop Belts: Trianglelab or DForce - Aliexpress Store
 - Connectors and Power Supplies: Arrow, Mouser, Digikey, etc
 - Silicone Wiring: Striveday - Amazon or Aliexpress
 - Heating Mat for Bed - Keenovo (no Built-in Thermal Fuse, use an external one)
 - PEI: Prozix on Amazon or CSHyde
 - Fasteners: Bolt Depot, McMasterCarr (do not purchase 18-8 Stainless Fasteners, Black Oxide Steel is Spec, Zinc Plated Steel is OK too)
 - Hotend Cooling Fan: Sunon or Delta (High Static Pressure Recommended)
 - Part Cooling Fans: Delta (12v and 5v only available)
 - Steppers: SteppersOnline
 - Side Panels (Transparent): TAP Plastics for Polycarbonate Panels or ABS Panels
 - Coroplast: Michaels Art Store or Your Local Home Improvement Store
 - Driveshafts: McMasterCarr Carbon Steel or High Speed Steel Dowel Pins or Equivalent
 - FSR Pin: McMasterCarr Stainless Steel Dowel Pins or Equivalent
:::warning
FYI: Be cautious and aware when buying kits from unofficial sources. There are currently no official sources (or plans to have any at this time) and you're taking a gamble in what you receive. There is a high chance that the parts you receive are not purchased from one of our recommended vendors (they are usually not the cheapest)
::: 

### What is the recommended wire for the cable chain
Striveday Silicone Wire, 20AWG for the Heaters and 24AWG for the remainder.

### Why are the wiring recommendations so strict?
The wiring recommendations are made out of an abundance of caution to hopefully prevent electric shorts and fires.

### Do I need to get extrusions from Misumi?
No you can get them elsewhere but you may have issues with the slot profile. There are many different extrusion profile "standards" and the Misumi profile is what's recommended to deal with rail offsets, bolt head sizes, etc. as designed.

### What are the "TPW" and "LCP-RCP" options for the frame?
These are the options specified to have Misumi tap and drill the hex key access holes in your extrusions. You can remove these options and do this yourself to save ~$40 USD. You will need appropriate tapping tools, oil, and patience to do it correctly which may add back up to $40 when it's all complete.

### The HNTAJ5-5 nuts are expensive. Do I really need this many?
No, you can substitute ball spring post-assembly nuts from Ali just as easily in 99% of the manual. You need 16 narrow M5 t-nuts for the gantry ends. You can substitute all M3 nuts for ball spring post-assembly if desired. Short M5 nut locations

### Why do you recommend CNA linear rails (chinese) vs a Hiwin or THK genuine rail?
 - We are not imparting cutting forces onto the carriages on the rails (ie: side loads), so the low preload and ok tolerances are good for this application
 - A Set of 7 rails is the cost of one genuine mid-grade THK rail.
 - Clean all of your rails, then grease them (there are numerous videos on youtube on how to do this). Pick your best rail for the X axis, 2 for the Y, use the worst on the Z

### What about the Clever3d PEI coated plate? It seems cool, and not having to apply the PEI sheet myself would be nice..
Several users have attempted them, and they are simply not workable with ABS. Testing showed they required a first layer temperature of at least 130C, which is approaching the failure temperature of the adhesive on the recommended Keenovo heater.

Their NON-PEI coated plates are a solid option though for those in Europe wanting to source a build plate.

If you own a PEI coated Clever3d bed, we recommend applying a sheet of your own PEI to it.

### Why did you use A4988s instead of DRVs or TMC stepper drivers in the design?
 - A4988s provide the best cost/noise/performance ratio. When run in the voron they are also quiet enough to rival most TMC driven machines. TMC steppers also cool poorly and often overheat on ramps based systems due to the tiny copper pour on the stepstick PCB. 
 - We also do not need the amperage capacity of the DRV8825s. 
 - A4988s are also usually included with ramps kits, so its a win for everyone.

### Will full kits/hardware kits be avalable for purchase:
There are no plans to sell kits of any kind.

## Tools
### What is a good crimping tool to use for terminating wires?
Engineer PA-09, PA-20, or PA-21. Yes, it's worth the cost.

### What is a good tool for grinding flats on the 5mm rods?
A Dremel or bench grinder work well. A flat file can also work fine. Use eye protection when working with high RPM power tools and fragile cutting discs.

### What are good brands for drivers to work with all of the fasteners?
Bondhus, Wiha, Wera


## Voron design decision
### Is the voron designed to print exotic materials?
No, the voron does not have a heated chamber, therefore it is not designed to print exotic materials. Exotics such as peek require build chamber temperatures of over 100C to print properly, which will result in everything in the chamber self-destructing. Belts are good to 80C max, china belt is good till 60C, steppers around 90C, printed parts start deforming around 70C. We recommend you purchase an industrial printer designed for this purpose if you intend to print with these materials so you dont end up with a fire on your hands. We also dont want lawyers on our doorstep for violating patents.

### Does V2.1 support direct drive? 
There are no plans to support anything other than bowden extrusion, pressure advance helps with 99% of the downsides and the mobius2 can print tpu.

### Does the V2.1 support dual extrusion
There are no plans to support dual extrusion at this time.

### Why doesnt the VORON have a chamber heater
There are a few reasons:
 - Big company patents and lawyers
 - Joe burning his house down
 - Its really easy to screw up for someone that doesnt have great amounts of experience with properly controlling/mounting them
 - If we spec something and people cheap out, there will be fires involved

### Why does the VORON not using IGUS products?
 - IGUS bushings exhibit a phenomenon called stiction, therefore in small movements the bushings will actually stick instead of gliding, at small detail, this causes detrimental issues.
 - The amount of slop required is unfavorable, tolerances are quite poor.
 - Bushing life is low for the price when compared to Misumi and even standard chinese offerings.


## Hardware substitution
### Can I substitute this part for that part?
You are welcome to make substitutions as you see fit but this printer is not a race to be as cheap as possible. It is designed to compete with many other high-end printers will still being affordable. Substituting parts may also have other unintended side effects and cause compatibility issues. Please feel free to ask for advice before any substitutions are made.

### Can I use my V-Slot extrusions from another project
No, MGN9 Linear rails cannot sit properly on them, and fall into them.

### Can I use 0.9 degree stepper motors rather than the speced 1.8 degree motors. 
 - They would not be recommended for the Z and E motors. These are already geared which give them better resolution. Going to 0.9 degree motors would mean they would then need twice as many steps to go the same distance as a 1.8 degree motor. This combined with microstepping results in more cpu load on your boards and would then start to limit how fast you can drive these. 
 - They may have some beneficial affect on the XY axis (AB motors) which don't have the gearing that the Z and E assemblies have. Don't expect miracles though, filament variance is another factor that starts to be an issue as well when attempting small detail. 
- While 0.9 motor can be a bit quieter, from all accounts in an enclosed Voron the fans are likely to make most of the noise. So any noise benefit would be negligible(edited)
- Using the BOM spec ramps and klipper with 0.9deg steppers will limit your theoretical travel speeds greatly, just running 1/16 microstepping with 0.9deg XY motors and pressure advance with a 1.8deg stepper on the Extruder is enough to easily overwhelm the board.

### Why does the VORON not use TMC2100, 2130, or 2208 drivers
 - The VORON specs 2A steppers at 12v to achieve its performance.
 - We are using the 2A spec OMC steppers purely for their holding torque capability. The characteristic of a low inductance/low coil resistance of the VORON spec motors is absolutely not inline with how these motors drivers operate. They are designed for high inductance steppers. 
 - If you really want to use TMCs just grab a genuine or cloned duet, you can put klipper on them now and they can drive high current steppers all day long with 2660s.
- If that's not an option you still want to use TMC stepsticks, add large heatsinks with active cooling and plan to significantly reduce travel and print speeds.

### Can I substitute RAMPS 1.4 for SKR Mini E3?
No, it has serious design flaws: A poor motor driver layout, small copper cooling area, and potential USB compatibility issues. The LCD header does not support the spec GLCD. - Volcom

### Can I substitute MGN(insert rail size here) for MGN9H rails?
No, VORON V2s are not designed for anything but a MGN9H

### Can I use alternate 2020 extrusions?
You can if they dimensionally match the below drawing:

## Firmware
### What firmware does the VORON use?
Klipper: Read this before asking any and all questions: [Klipper Overview](https://www.klipper3d.org/Overview.html)

Furthermore see [Voron Klipper](/EROaLkSjSqaKzFZkPuqZxg) for a step-by-step guide of the setup.

### I get error `Option 'samples' is not valid in section 'quad_gantry_level'` when updating klipper to latest version
With the recent update both 

`samples:`

 and 

`sample_retract_distance: `

 eed to be moved from the `[quad_gantry_level]` section to the [probe] section - you should also re-flash your arduinos and re-run 

`/home/pi/klipper/scripts/install-octopi.sh`



## Building a Voron
### What should I do with the flanges from the 20t when building my new 80t pulleys?
Hold onto them for a special suprise

### Using the number of washers shown in the manual, things are too tight or too loose 
Depending on where you sourced your washers they may have different tolerances. The VORON is designed around 1mm thick shim washers, you can buy either 0.5mm or 1mm thick ones and adjust accordingly. Standard washers are sized as follows: 1mm +0.2mm -0.00mm usually.

### The part in the manual on page 37 with the clear top and grey cable is the inductive probe - held by the two probe retainers.
![](https://i.imgur.com/6zs7vFm.png)


###### tags: `Voron` `FAQ`