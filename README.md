# Project: EasyPAPR - a DIY powered respirator
# **Disclaimers:** 
### _No doctors or safety scientists were involved_
### _Some HEPA filters may contain glass and injure your lungs, be careful!_
### _CO2 buildup from improper design can be fatal_
### _This is a thought experiment, build at your own risk_
### _This may not work at all_
### _This could injure or suffocate you_
### _Small parts / choking hazard_
# Overview
This project is exploring how to build a PAPR - Powered Air Purifying Respirator out of ordinary household items.

|     |  |  |
|---------|-------|-----| 
| <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/helmet_completed.jpg" width=350> | <img src="https://github.com/greglarious/EasyPAPR/blob/master/pictures/full_assembly.jpg" width=350> | Video: [![Demonstration Video](http://i3.ytimg.com/vi/X4n29OlbJjI/hqdefault.jpg)](https://www.youtube.com/watch?v=X4n29OlbJjI) |

# Description 
A 12v blower pulls air in through a 0.1 micron HEPA filter disigned for a vacuum cleaner. The air is pumped out through a hose into a helmet. Each component and assembly step should have multiple alternative solutions to account for limited availability of parts, tools, and assembly skill.

# Background
The Covid-19 pandemic has spurred a great deal of creativity channeled into many projects. This project is aimed at being helpful in the intermediate to long-term timeframe. In between the immediate urgent need for homemade cloth masks and the eventual wave of professional medical products being available, I believe there is a need for a solution that is simple to build, effective, and made out of ordinary materials. The agenda at this time is to iterate on refining and measuring the design, not to "build N number of masks and rush them to X location for immediate use".

# Call for help
As this project progresses and multiple prototypes are built, the problem transitions from raw engineering to objective measurement and refinement. What I really need right now is good scientific advice in these areas:
- How can the effectiveness of this design be safely tested? (see Testing Methodology below)
- What other safety risks am I failing to consider?
- How can this design be made more simple using less materials without losing effectiveness?

# Design
## Questions and Assumptions:
- Is this HEPA filter safe to breath through (no glass fibers) ?
- Is this HEPA filter able to remove dangerous particles such as virus and bacteria?
- Does positive pressure eliminate the need for an airtight solution?
- Is this safe to use regarding delivery of enough air and CO2 buildup? 
- Can this can be used many times without changing the filter?
- Can the parts other than the filter be effectively cleaned?

## Goals:
- Use measuring devices to objectively demonstrate effectiveness
- No tape/glue: fully disasseblable for cleaning purposes
- Propose multiple commoDesignn materials for each component
- Propose multiple assembly techniques to using tools present in ordinary homes
- Durable
- Comfortable

# Current status
## Already built
- Testing rig without a helmet. Filter connected to pump and hose going into a measurement chamber
- Several prototypes for walking around and testing

## ToDo:
- Use 265nm UV LEDs shining on both inside and outside of HEPA filter material
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
  - The PMS7003 only goes down to 0.3 microns, is that good enough?
  - The raw data from the PMS7003 seems to fluctuate a lot.  What math should I be doing to summarize?
  - What is a realistic goal for reduction with the filter that will demostrate some protection?
- Measure / monitor CO2 buildup; using an SGP30 Gas Sensor
  - What levels of CO2 are dangerous?
  - Is testing the design ok or should there be an audible alarm for high levels?
- Use various harmless substances with a human detectable odor that fit a particle fitler test
  - What harmless substances with a smell exist and what particle sizes do they represent?
- Battery life / burn in test
  - run on the workbench with a timer
- Durability testing
  - do various movement exercises while wearing and see what breaks first
  - ok to wear while walking the dog?
  - probably not afe enough to wear it to the grocery store yet as that would risk actual infection?
