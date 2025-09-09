KiCAD 8.x files created.

A reworked layout of Unexpected Maker's 7SegNeo Display project. Chain these addressable LED modules together to make a large 7-segment display. Control via any micro-controller just like you would control a strip of RGB LEDs. Custom library made by Unexpected Maker.

<img width="652" height="972" alt="render front" src="https://github.com/user-attachments/assets/5caece53-5ee2-4ed3-8c98-09c9328bfd55" />

![fart neo7seg good gif](https://github.com/user-attachments/assets/3b003526-7364-4982-a5ff-64db2d3d8d25)
![P1100468](https://github.com/user-attachments/assets/04991485-a8a6-4b6f-b4c0-e9e1891ce40b)

Assembly Required:
Each moduled has a resistor footprint at the Data In line. The first module in the chain requires a ~220-330 ohm resistor soldered here. Each moduled next in the chain requires this jumper closed; 0-ohm resistor or just a solder blob.
![P1100470 - Copy](https://github.com/user-attachments/assets/85c101c0-1d2d-42f9-a69e-186f49d5e1fe)

Change list: bumped-up passives footprint to 1206, finessed trace/ copper pour layout; slightly larger PCB area, larger mounting holes, decimal place pixel same footprint as all other pixels.
Created some 3D printable mounting brackets to expidite building projects like a clock/scoreboard. 

RGBLEDs: 1568-16347CT-ND or https://www.aliexpress.us/item/3256802466699315.html
