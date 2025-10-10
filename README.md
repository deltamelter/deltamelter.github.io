<img width="1607" height="685" alt="image" src="https://github.com/user-attachments/assets/e3b0826f-c2fc-4259-88fe-d24ebb07678c" />
PS port:
I connected wires 1 and 6 (soldered to the PS battery connector PCB) with a small protective resistor, and the error message disappeared.
It seems that pin 1 of the PS serves as a range selection switch:
Open = 11-15 VDC range
to GND = 40-59 VDC range

<img width="3180" height="1233" alt="image" src="https://github.com/user-attachments/assets/3b2301d9-a772-4fd0-9084-d99b9e2374b1" />
Delta (EB) port:
Added a 1kΩ resistor between pin 4 (12V) and pin 6 (GND) in the EB connector to pull the enable line low. This signals the BMS to connect the internal battery to the EB port.
