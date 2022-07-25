# OpenScan - PCB

The heart of the OpenScan is the OpenScan-PCB (or Pi Shield) which supplies all components with power and serves as connectivity hub between all components. The current version (v1) sold is fully functional and can be hand-soldered quite easily without any special components in use. Wiring diagram can be found [here](https://drive.google.com/file/d/15dHPhmN0gLu5s5aGFLwUulbkThmojQXg/view) and the documentation/manual [here](https://drive.google.com/file/d/1dsRXQuZrLWvM27U1WFC0Ot8rcSIoJQud/view). There is also a v2 in the making, however, without ETA. The next version will inlcude user suggestions/mods so we make them accessible to the broader community.

The current fully-functional OpenScan-PCB v1 features:

# OpenScan-PCB v1 (current)
- two stepper drivers A4988
- two controlable 12V outputs for the ringlight module
- uses existing 12V -> 5V DCDC converter
- opto-coupler for external camera trigger
- various GPIO for additional feature implementations for power users

There is a newer version in the making that will include more potential features, albeit currently not in use by the OpenScan software

# OpenScan-PCB v2 (T.B.A.)
- smaller footprint than v1
- full accessible pass-through GPIO pin header like HATs and addon boards for the Raspberry
- up to three motor drivers with end stops
- configurable microstepping and functions to have maximum compatibility with other stepper drivers
- Enable/Disable pins for the drivers
- reverse voltage protection for the RPi
- pull-down and pull-up resistors
- extra controllable pin to the ringlight (not in use for anything at the moment)

# Ringlight v2
- simple design containing two series of four 1W LEDs driven by 12V 
- mounting holes for Arducam and RaspberryCam cameras
- extra controllable pin from the Raspberry (not used right now, free to use for power users)
