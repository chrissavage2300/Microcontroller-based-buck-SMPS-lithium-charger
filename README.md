# Microcontroller-based-buck-SMPS-lithium-charger
PIC18F13K22 Based lithium buck coverter

Based on app note SLAA-287-Li-Ion Battery Charger Solution Using an MSP430™ MCU from Texas Instruments. 

Note: U2, JP3 and R5 are not used. The internal VREF is used.

JP6/7 have been replaced with 1206 LEDs

R6-50ohms may work rather than 0.

JP5 limits the input voltage to 5V, so IC1 wouldnt need to be populated in this case. It therefore may also work off of a USB-C connector but this hasnt been tested. 

Pins RC1 and RC2 are not used even though they are called out.
