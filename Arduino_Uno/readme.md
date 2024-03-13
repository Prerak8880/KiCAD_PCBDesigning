# Arduino Uno CH340

**<p>An Arduino Uno CH340 is an Arduino Uno board that uses the CH340 chip as its USB-to-Serial converter. This chip is more cost-effective compared to the Atmega16U2 used in the official Arduino Uno Rev3 boards. The CH340 board is functionally identical to the Uno Rev3, and it can run any Arduino sketch without modification. </p>**

<br>  The 16U2 acts as a USB-to-serial converter. The Arduino bootloader in the Atmega328P allows the chip to be programmed via UART(serial port). Older computer systems had serial ports that could have been connected directly to the Atmega328P. But USB is ubiquitous these days and a USB to serial converter is needed to mimic the serial port over USB. Usually, FTDI chips are used, but the Arduino guys decided to go with 16u2 for some reason. The best part is that you can also program and create your applications on the 16u2 if you have an In-circuit Serial Programmer. 

<br>
<br>
## Comparision(CH340 v/s Rev 3) ##
<br>
- CH340<br>
  - Compatibility Issues.
<br>
![9](https://github.com/Prerak8880/KiCAD_PCBDesigning/assets/96664052/ef4a9d8c-d35d-40fb-8653-3dcf75952d9e)

     
<br>
  - Upload Speed<br>

    
  - Power Consumption<br>

    ![10](https://github.com/Prerak8880/KiCAD_PCBDesigning/assets/96664052/eeede216-d19e-48e7-94a9-e43b778c8b42)<br>
  - Timed Consumption<br>

    ![10](https://github.com/Prerak8880/KiCAD_PCBDesigning/assets/96664052/e821f810-14f4-4027-ae23-4e0e5d2165af)<br>


## Reference<br>
-- https://makersportal.com/blog/2019/3/12/testing-the-arduino-ch340-board






