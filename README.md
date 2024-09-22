
# DIY_EvilCrowRF_v2-el_Cheapo_version PCB

"The EvilCrowRF_v2" is a radio frequency device for pentesting and Red Team operations, this device operates in the following radiofrequency bands:

    300Mhz-348Mhz
    387Mhz-464Mhz
    779Mhz-928Mhz

![ECRF-icon](https://github.com/user-attachments/assets/c1e1ef7d-43e0-48da-a2c6-e7290fa95330)


    
# The DIY_EvilCrowRF_v2-el_Cheapo_version is a PCB that brings all the awesome features from the original hardware with over-the-shelf parts, affordable and easy to build experience for a lot of fun and profit.



![ECRF-jeito-de-Microbio](https://github.com/user-attachments/assets/65c0696b-b137-4916-8f5d-ffbf1340451d) ![ECRF-jeito-de-Microbio_back](https://github.com/user-attachments/assets/f59e6205-acda-447a-8af6-b16c59ecfd91)







# Requirements:



1.- TI CC1101-v2 module which is currently the most available version everywhere (we need 2 modules).

(The CC1101_v2 has 8pins, blue color and with two circle-holes).

Like this one:

https://www.aliexpress.us/item/3256806241609769.html





2.- ESP32 DevKit_v1 This board has 30-Pins, and the chip ESP-WROOM-32 footprint. 

See here:

https://www.aliexpress.us/item/3256801462536246.html





3.- MicroSDcard module (6 pin)

This one works:

https://www.aliexpress.us/item/3256805794981947.html



However, there is a gotcha. This module will be soldered in the back of the PCB.

The order of the pins has to be from left to right:

CS, SCK, MOSI, MISO, VCC, GND. 


In the case of this MicroSDcard module, the headers need to be desoldered. 

New headers need to be soldered from the oposite side of the module.

For reference see picture below.




4.- The PCB for this easy to build device DIY_EvilCrowRF_v2-el_Cheapo_version.

Download the ZIP file from the release section of this page and sent it to print to your favorite PCB manufacturer. 




5.- 2x tactile push buttons (for instance 6x6x6), 2x 10k resistors, a switch, Iron, solder, flux, headers, etc.



6.- A MicroSDcard

Any MicroSdcard (no bigger that 32 GB) should work.



7.- There is the need for a battery to provide 5 volts to "el-Cheapo" through the entry labeled "5V-IN". 

An alternative option could be sacrifying an USB cable and solder the Positive and Ground ends to the board and plug it to some small powerbank.


Note: 

Powering the device through the ESP32 USB port will not provide power to the CC1101 modules or the SDcard. Therefore, el Cheapo will not work.



# The result:

Putting things together the device will look like this one:


Btw, the photo quality on these pics don't really show the beauty of the final build. But, whatever.


![Cheapo-front-1](https://github.com/user-attachments/assets/d541bb76-af29-45c7-80c0-423b46bc68c6) ![Cheapo-1](https://github.com/user-attachments/assets/aa6f9d0d-b4c9-45b7-adb8-74291d0009ab)





Now that the device is ready, get the firmware and go outside to play.

Please use this device responsibly. 


# There are several firmware options to use this hardware:





1.- The original project page and follow their directions.

https://github.com/joelsernamoreno/EvilCrowRF-V2



2.- Another option is the alternate firmware from h-RAT.

https://github.com/h-RAT/EvilCrowRF_Custom_Firmware_CC1101_FlipperZero



3.- If you are masochist there is one complex option, but at the same time powerful and rewarding.

https://github.com/rfquack/RFQuack





# LICENSE


Distributed under the MIT License. See LICENSE.txt for more information. The tool/device is for educational purpose only and the author does not condone any illegal use. Use as your own risk.






































