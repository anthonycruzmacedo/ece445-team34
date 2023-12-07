# Angelica Worklog
## 09/26 TA Meeting Notes
- things to ask during meeting
- subsystem requirements
- schematic/PCB, ask if they have a layout

- design document
- more information in the subsystem overview section, picture for schematic
- tolerance analysis
- block diagram is ok, add paragraph
- glance at ethics

## 09/26 Golecki Meeting Notes
### topics
- are there any subsystem requirements (eric)
- schematic so that we can make it into a PCB
- check out the sensor resistors
- what do we need to accomplish

### notes
- intelliwheel (?)
- no schematic but there's a presentation (Golecki will send)
- https://www.programmableair.com/
- copy Golecki when messaging the Harvard person, be respectful (the other one has more ports)
- look into shovel valve
- smart dude: bethke2@illinois.edu
- binary lookup table, state machine type deal
- SN74HC shift register
- max number of sensors: find out the max number that could fit in size of a cushion
- sensor fusion, linear interpolation
- harvard valve: 14 PSI, solenoid valves
- discrete ADC
- $150 per team

## 10/03 Golecki Meeting cont. 
- will be using 30 sensors in 6x5 array (show mockup)
- silicon mold class 8-9:20am next tuesday
- figure out distributions with cushion, after cushion, etc. (collect data to figure out thresholds)
- ask Jason about the valve thing, maybe constrain to tailbone
- inflation: how many levels (ex. 2 would be full inflated or full deflated), zero vs. reduced pressure
- test out the sensors and then send link to Golecki, will be at the garage

## 10/03 Jason/Isaiah Meeting
- 6 outputs cap
- levels of inflation: they are looking into height of inflation, probably more of a on/off thing, at max 3 levels
- distribution: maybe just test it out after building the array to figure out the range of values, see what the readings will look like

## 10/17 Meeting with Jeff
- there is a function to do ADC, GPIO can be analog or digital
- add testing pads in schematic

## 10/17 Golecki Meeting
- FSRs just ordered lol
- Harvard dude can help, set up call with him
- can we inflate (is it powerful enough) with weight on it

## 10/24 Meeting with Jeff
- he has STM dev board lying around, we can get started with working on the software while we are waiting
- individual report: just write like a paragraph of what you have done, the rest can be copied from design doc, just reach 5 pages, submit on Canvas on time
- deadline for PCB 3 is tonight like last time (but they ordered on Thursday the past two weeks), could risk submitting it tomorrow
- Final Demo --> 150 points: 20 points complexity, 30 points PCB, focus on what we have right now
- let Jeff know after we order parts which we should do today

## 11/09 Meeting with Jesse
- dont use the vacuum and just connect both
- 3mm outer diameter, 2mm inner diameter for the tubing (but manifold may be different than the pump)
- look at the slides for circuit diagram and such
