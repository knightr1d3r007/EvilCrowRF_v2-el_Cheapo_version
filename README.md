
# DIY_EvilCrowRF_v2-el_Cheapo_version PCB

"The EvilCrowRF_v2" is a radiofrequency hacking device for pentesting and Red Team operations, this device operates in the following radiofrequency bands:

    300Mhz-348Mhz
    387Mhz-464Mhz
    779Mhz-928Mhz

![ECRF-icon](https://github.com/user-attachments/assets/c1e1ef7d-43e0-48da-a2c6-e7290fa95330)


    
# The DIY_EvilCrowRF_v2-el_Cheapo_version is a PCB that brings all the awesome features from the original hardware with over-the-shelf parts, affordable and easy to build experience for a lot of fun and profit.



# Requirements:


1.- TI CC1101-v2 module which is currently the most available version everywhere (we need 2 modules).

(The CC1101_v2 has 8pins, blue color and with two circle-holes).
Like this one:
https://www.aliexpress.us/item/3256806241609769.html



2.- ESP32 DevKit_v1 This board has 30-Pins, and the chip ESP-WROOM-32 footprint. 
See here:
https://www.aliexpress.us/item/3256801462536246.html


3.- MicroSDcard module (6 pin)
this one works;
https://www.aliexpress.us/item/3256805794981947.html
However, there is a gotcha. This module will be soldered in the back of the PCB. 
The order of the pins has to be from left to right: CS, SCK, MOSI, MISO, VCC, GND. In the case of this MicroSDcard module, the headers need to be desoldered. The new headers need to be soldered from the oposite side.
see picture below.


4.- The PCB for this easy to build device DIY_EvilCrowRF_v2-el_Cheapo_version.
Download the ZIP file from the release section of this page and sent it to print to your favorite PCB manufacturer. 


5.- Iron, solder, flux, headers, etc.







