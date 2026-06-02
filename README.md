Hi. Welcome to the repo for Ricardo-Cappy.

Ricardo-Cappy is a custom HAT (Hardware Attached on Top) for the Raspberry Pi 5 to be used on the Payload lander for the 2026 ICLR launch.

It contains IMU sensors based on Ricardo-PickleRick, wirecutter modules, motor drivers for deploying landing legs, GPS and Radio capabilities as well as power systems for both the Raspberry Pi and the onboard components.

Contents:

-Hardware - contains the KiCad schematics and PCB layouts for Ricardo-Cappy, including symbols and footprints for parts not in the ICLR library. This is necessary for viewing and editing the KiCad files on your own device. 

To use the hardware files:
1. Install the ICLR symbol and footprint library (see their repo for detailed instructions, I forgot the link but you can use google)
2. Clone the repository onto your computer.
3. Install my custom libraries into KiCad (see instructions in KiCad documentation)
