# Cognitive-Home
This project uses the MSP430G2553 to simulate a simple version of Home Automation. 
The project controls the lighting and temperature in a room. 
If the temperature is beyond 25 degrees, the microcontroller would turn on the airconditioner. 
If between 20 and 25 degrees the fan is instructed to turn on. 
For temperatures below 20 degrees, none of the devices are turned on. 
As for the lighting in the room, the microcontroller makes use of an external LDR and controls the lights according to a pre decided threshold value. 
This was coded on the IAR Workbench. 
