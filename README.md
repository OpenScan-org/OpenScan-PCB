# OpenScan - PCB design area :)

I hope, that some more skillfull people help to (re-) design the PCBs used in the OpenScan Hardware. I am very open for further discussions and feature requests and this repository should be the place for all PCB-related ideas and issues.

# Pi-Shield v1 (the current version)
- two stepper drivers A4988
- two controlable 12V outputs for the ringlight module
- uses existing 12V -> 5V DCDC converter

# Pi-Shield v2 (which well long overdue)
Here, I am trying to collect all ideas for an improved version:
- same overall footprint as the board v1 (?) or total restart ?
- internal DCDC regulator based on the Texas Instruments TPS5430DDAR (or similar?)
- at least two endstops
- controllable (maybe even dimmable) 12V output for the ringlight module (PWM does not work, as the camera uses a rolling shutter)
- at least two stepper motor drivers (silent stepper drivers, connected enable pin, ...)
- reverse voltage protection (?)
- at least two switcheable outputs for 12V, 5V and maybe even 3.3V comming from the RPi (for example using Mosfet: Shikues SK337N)
- ... ?


# Ringlight for Pi Camera v1.3/v2.1 and Arducam IMX519
- simple design containing two series of four 1W LEDs, where each array can be driven by 12V (without additional cooling)
- [footprint of LED](https://www.pcboard.ca/image/catalog/products/leds/led-bead/led-bead-dimensions.jpg)
