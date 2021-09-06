# mister-pcbs

This site contains some stuff I have built for the excellent Mister project. You can more about the Mister project here: https://github.com/MiSTer-devel/Main_MiSTer/wiki

I tinker with electronics, release stuff when I feel like it and I make it public when it's maybe not perfect. I'm not an electronics expert, so I may not always know what I'm doing. I learn the necessary electronics as I use it. Use at your own risk.

Be smart. Don't just trust the stuff I offer for download here. Take a look at the schematic and the PCB design beforehand. 

Feedback is always very welcome :smile:

## Midi PCB for Mister
This is a PCB for the Mister FPGA that extends midi functionality through the USB port.

![image](https://user-images.githubusercontent.com/884834/132215326-3aca588a-d103-4381-a1b3-bc4a5d4aca4b.png)
![20210906_140027](https://user-images.githubusercontent.com/884834/132215819-9e92a566-bedc-47fa-956c-ae22fc4e4931.jpg)
![20210906_140224](https://user-images.githubusercontent.com/884834/132215739-6172dcc0-fc90-4df5-830a-d9d2765d3e1a.jpg)


Schematic: https://github.com/bzeiss/mister-pcbs/blob/main/mister-midi-pcb/pdf/schematic.pdf

Gerbers: https://github.com/bzeiss/mister-pcbs/blob/main/mister-midi-pcb/gerber/mister-midi-pcb-v1.1.zip

### BOM

| Quantity      | Label                   | Part                                | 
| ------------- | ------                  | -------                             | 
| 2             | R6,R7                   | 0805 10 ohm resistor                | 
| 2             | R4,R5                   | 0805 33 ohm resistor                | 
| 6             | FB1,FB2,FB3,FB4,FB5,FB6 | 0805 Ferrite Bead                   | 
| 1             | C1                      | 0805 100nF ceramic capacitor        | 
| 2             | C2,C3                   | 0805 10uF tantalum capacitor        | 
| 1             | R1                      | 0805 2k ohm resistor                | 
| 3             | R3,R8,R9                | 0805 220 ohm resistor               | 
| 1             | R2                      | 0805 470 ohm resistor               | 
| 1             | D1                      | 0805 1N4148 diode                   | 
| 1             | U1                      | SMD H11L1 opto-coupler              | 
| 1             | U2                      | SMD 74HC14                          | 
| 1             | D2                      | 0805 LED green                      | 
| 1             | D3                      | 0805 LED blue                       | 
| 1             | D4                      | 0805 led white                      | 
| 1             | U3                      | LM1117-3.3                          | 
| 1             | J2                      | USB3 Type-A connector                | 
| 3             | J1,J3,J4                | DIN5 Midi connector                 | 

