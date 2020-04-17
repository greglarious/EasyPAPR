# Project: EasyPAPR - a DIY powered respirator
# **Disclaimers:** 
### _No doctors or safety scientists were involved_
### _Some HEPA filters may contain glass but EnviroCare filters to not_
### _This is a thought experiment, build at your own risk_
### _This may not work at all_
### _This could injure or suffocate you_
### _Small parts / choking hazard_
# Overview
How to build a PAPR - Powered Air Purifying Respirator out of ordinary household items
<img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_completed.jpg" width=350>
<img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/full_assembly.jpg" width=350>


Demonstration Video:[![Demonstration Video](http://i3.ytimg.com/vi/X4n29OlbJjI/hqdefault.jpg)](https://www.youtube.com/watch?v=X4n29OlbJjI)

# Description
A 12v blower pulling air in through a vacuum 0.1 micron HEPA filter and pumping out through a hose into a helmet made out of kite fabric and a 2 liter plastic bottle. The ultimate goal is to solve each component and assembly problem in multiple ways to account for limited availability of parts and various degrees of skill.
# Design Principles
## Assumptions:
- Assuming this HEPA filter is safe to breath through (no glass fibers) and filters out "the bad stuff"
- Positive pressure eliminates need for an airtight solution
- Air path entering from top of head to exiting at chin provides enough air to safely breathe
- This can be used many times without changing the filter

## Goals:
- No tape/glue, fully disasseblable for cleaning purposes
- Propose multiple parts / techniques for every step to ensure more people can do this
- Durable
- Comfortable

## ToDo:
- 265nm UV LEDs shining on both inside and outside of HEPA filter material
- Case with belt to enclose both battery and filter. Allow air in but keep UV light from escaping
- Speed controller for motor
- Reshape hood to leave ears exposed
- Nose scratcher?
- Drinking tube?
- Red Propeller on top and small vent to make it spin!

# Parts List
| Part | Image |
|------|-------|
| EnviroCare Hoover 3100 replacement HEPA filter | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/filter_opening.jpg" width=200> |
| 12v squirrel cage blower fan | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/blower.jpg" width=200> |
| Foam Gasket | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/gasket.jpg" width=200> |
| 12v battery | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/battery.jpg" width=200> |
| Faceplate cut from clear plastic. Source is 2 liter beverage bottle or large pretzel container | |
| inline 3A automotive fuse and holder | |
| Dishwasher drain hose | |
| Airtight nylon kite fabric | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_pattern.jpg" width=200> |
| clear 2 liter beverage bottle or pretzel container | |
| Aluminum strips (Aluminum Roll Valley Flashing) | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/clamp.jpg" width=200> |
| 14 - #6-32 1/4 inch long machine screws with acorn nuts |  |
| needle and thread |  |
| elastic (cut from ace bandage, inside bungee cord, old waistband, rubber bands |  |

# Assembly 
## Clamping faceplate to fabric
Faceplate is a piece of clear plastic from a beverage bottle. Step here is to clamp it onto the fabric with some bent pieces of aluminum and machine screw/nut.
| Step | Image |
|------|-------|
| Drilling hole through faceplate | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_drill_clamp.jpg" width=250> |
| Screwing clamp into place | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_clamps.jpg" width=250> |
| Attached faceplate | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_faceplate_attached.jpg" width=250> |

## Attaching blower to filter with gasket
Blower has a circular air-input and the filter has an oval exit. Need adapter gasket to fit the two together in an airtight way.
| Step | Image |
|------|-------|
| Gasket on filter | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/filter_attached_to_gasket.jpg" width=250> |
| Gasket on blower | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/blower_attached_to_gasket.jpg" width=250> |
| Gasket between filter and blower | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/blower_attached_to_hose.jpg" width=250> |

## Helmet Construction
Lightweight helmet to offer protection. No need to be airtight due to positive pressure design.
| Step  | Image |
|-------|-------|
| Sewing top of helmet | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_sewing_top.jpg" width=250> |
| Air exit holes (melted) | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_air_exit.jpg" width=250> |

## Headstrap for stabilization and directing airflow 
Headstrap stabilizes helmet position, attaches to air hose at back, and directs airflow to exit at the top sides of the head pointing down.
| Step | Image |
|------|-------|
| Basic comfortable headstrap design |  |
| Attachment for air hose at back |  |
| Split airflow 2 or 3 ways |  |
| Direction tubes leading to top/front sides |  |

# Testing Methodology
- Measure / monitor particle reduction effectiveness with with a PMS7003 high precision laser dust sensor
- Measure / monitor CO2 buildup; using an SGP30 Gas Sensor
- Use various harmless substances with a human detectable odor that fit a particle fitler test
- Battery life / burn in test
- Durability test
