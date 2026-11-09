# MyFirstCustomKeyboard

## TL;DR

This is my first custom keyboard build, as an introductory project to PCB and Hardware Design and getting use to making projects like these. This is a 60% mechanical keyboard, using Brown MX Switch Keys (PCB can support other types including Cherry MX with **Hot-swap not included**) and a Raspberry Pi Pico W as the brains. It also features a charging system, using a LiPo battery paired with a MCP73831-2-OT charging controller for battery health and monitoring. The keyboard connects via Bluetooth (firmware will be available) and charges using USB-C. 

## Software used

KiCad was used in PCB design to create the schematic and PCB design as well as generating the manufacturing files. An online ```.dxf``` file converter was used to convert the images to Silkscreen. I then used Onshape (Web-based CAD tool) to design teh case for the keyboard. Firmware will be added later.

## PCB

The PCB design includes 50 keys, 54 resistors, a MCP73831-2-OT charging controller, USB-C input and a Raspberry Pi Pico W. Here are some images of the PCB:

