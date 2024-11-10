KiCAD 8.x files
A reworked layout of Unexpected Maker's 7SegNeo Display project. Chain modules together to make a large 7-segment display! Control via any micro-controller just like you would control a strip of RGB LEDs.

![fart neo7seg good gif](https://github.com/user-attachments/assets/3b003526-7364-4982-a5ff-64db2d3d8d25)
![P1100468](https://github.com/user-attachments/assets/04991485-a8a6-4b6f-b4c0-e9e1891ce40b)

Assembly Required:
Each moduled has a resistor footprint at the Data In line. The first module in the chain requires a ~220-330 ohm resistor soldered here. Each moduled next in the chain requires this jumper closed; 0-ohm resistor or just a solder blob.

Change list: bumped-up passives footprint to 1206, finessed trace/ copper pour layout; slightly larger PCB area, larger mounting holes, decimal place pixel same footprint as all other pixels.
