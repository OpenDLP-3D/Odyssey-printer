# Odyssey-print
DLP Printer Software and Firmware for Beaglebone Black with DLP-Cape.
Odyssey-Printer is a headless Python control software for the DLP 3D Printers, designed to run on the Beaglebone Black and use the DLP-Cape. The software aims to be almost 100% Python with the exception of the PRU code for doing step generation and driving of stepper motor axes. 

General Specs:
- Headless program, starts at boot as a user (every ready to go after the pritner turns on)
- 100% Python Codebase 
- PRU Step generation and stepper control
- Designed for Beaglebone Black and DLP-Cape
- Compatible with USB based projectors
- Projector output via HDMI

