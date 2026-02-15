# EldenPad
Hello! This is my custom macropad for hackclub x amd Blueprint 
## Description
- This thing is chonky massive(i couldnt fit my wires and my engravings on a small one)
- I have a 0.91 inch OLED display displaying a hollow knight image, im gonna animate it and put a clock on it later on
  <img width="128" height="32" alt="hollow knight" src="https://github.com/user-attachments/assets/5b2f6370-c5bb-4591-9d25-463d38eb6690" />
- I got 6 LEDs with RGB
- I have a rotary encoder which controls my volume
- I have 9 keys (including the rotary encoder switch)
- I have a malenia and alaxander engraving on it :)
- I have two custom keycaps, one being the sekiro death symbol and the elden ring logo.
## PCB
**schematic**

<img width="807" height="588" alt="schematic" src="https://github.com/user-attachments/assets/7f147162-45c6-4f4a-a7f5-519be0ed544c" />

Even though it says MINI LEDs the, footprint is mini E

**pcb**
<img width="589" height="649" alt="PCB" src="https://github.com/user-attachments/assets/cc07e3a5-b5f8-4dcc-a168-a603f672bac5" />
The wires look super messy, this is my first time and idk how to make it cleaner.

## CAD

This was the most fun part of the entire process, even though it was painful. I used the education version of autodesk fusion for all this.

<img width="1368" height="805" alt="cad1" src="https://github.com/user-attachments/assets/6f4e6250-7432-45f0-86f8-99a0a8c82701" />
<img width="1314" height="800" alt="cad2" src="https://github.com/user-attachments/assets/937700b9-1ed2-4d66-a886-110fe59f6492" />
<img width="976" height="821" alt="cad3" src="https://github.com/user-attachments/assets/ca2bcf29-97d5-4f4b-8685-205026299517" />
<img width="767" height="773" alt="cad4" src="https://github.com/user-attachments/assets/22732373-4074-41ee-9855-4eb27ed90424" />

## Firmware

This was by far the HARDEST part of the entire process as it was really confusing ( ive never writen code in C before so i had to learn everthing from GfG)
I wrote my firmware in QMK and you can find it in the REPO, the fully compiled one in the Production section

## BOM
- 1 Seeed XIAO RP2040
- 8x MX-Style switches
- 6x SK6812 MINI - E LEDs
- 9x through-hole 1N4148 Diodes
- 1 SSD1306 128*32
- 4x M3x16mm screws
- 4x M3x5mx4mm heatset inserts



