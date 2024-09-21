
# DIY_EvilCrowRF_v2-el_Cheapo_version PCB

"The EvilCrowRF_v2" is a radiofrequency hacking device for pentesting and Red Team operations, this device operates in the following radiofrequency bands:

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




5.- 2x tactile push buttons (for instance 6x6x6), 2x 10k resistors, Iron, solder, flux, headers, etc.



6.- A MicroSDcard

Any MicroSdcard (no bigger that 32 GB) should work.



# The result:

Putting things together the device will look like this one:


![Cheapo-front](https://github.com/user-attachments/assets/c83c2fd1-5090-4b1f-92e2-ed57f02b3df9) ![Cheapo-back](https://github.com/user-attachments/assets/bfd78192-e914-464c-b79c-d5313d308f19)




Now that the device is ready, get the firmware and go outside to play. There are few option to use this hardware:




1.- The original project page and follow their directions.

https://github.com/joelsernamoreno/EvilCrowRF-V2


2.- Another option is the alternate firmware from h-RAT.

https://github.com/h-RAT/EvilCrowRF_Custom_Firmware_CC1101_FlipperZero


3.- If you are masochist there is one powerful but complex option:

https://github.com/rfquack/RFQuack

































