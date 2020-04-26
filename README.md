# Particle Boron ublox SARA-R4 Firmware Programmer 

## Hardware
### Printed Circuit Board 
I'm sharing the PCB design on  OSH Park. OSH Park produces high quality PCBs for little money. They come in lots of three and cost 9$. Feel free to order some for you. 

OSH Park [Boron-ublox-FW-Programmer](https://oshpark.com/shared_projects/7IBDIvOl).

The programmer can be built with either USB jack or USB cable, depending on which fits best your needs. For the version with USB cable I used one of the USB cables that Particle supplied with their development kits. I recommend to use a hot air gun to solder the USB jack.


![Programmer with USB jack](Hardware/Doc/Images/Boron_FW_Progr_01.JPG) Programmer with USB jack | ![Programmer with USB cable](Hardware/Doc/Images/Boron_FW_Progr_02.JPG) Programmer with USB cable |
|:---:|:---:| 

### Bill of Materials

| No. | Qty. | Mouser Part No.                                                                | Description                              |
| --: | ----:| ------------------------------------------------------------------------------:| ----------------------------------------:|
| 1.  |    1 | [485-2886](https://www.mouser.ch/ProductDetail/Adafruit/2886)                  | Feather - 12 / 16-pin Female Header Set  |
| 2.  |    1 | [485-2430](https://www.mouser.ch/ProductDetail/Adafruit/2430)                  | Pogo Pins Needle Head (10 pack) - P75-B1 |
| 3.  |    1 | [490-UJ2-MIBH2-4-SMT](https://www.mouser.ch/ProductDetail/490-UJ2-MIBH2-4-SMT) | USB Connectors USB 2.0 micro B jack      |

## Building the Firmware Programmer

1. Solder the USB jack or the USB cable to the PCB (I recommend fixing the USB cable to the PCB with a zip tie as shown above). 
2. Solder the female headers to the PCB. 
3. Soldering the pogo pins requires a simple trick, which helps to align them precisely and gives them enough contact pressure. 
	1. Build a sandwich of the programmer, an empty PCB and a Boron as shown below. 
	2. Put the pogo pins through the pads and check that they hit the center of the test points. 
	3. Solder the pogo pins without applying additional pressure to the pins.
	
	<img src="Hardware/Doc/Images/Boron_FW_Progr_04.JPG" title="Programmer with USB jack" width="400" /> <br> Programmer with emtpy PCB used for pogo pin alignment | 
|:---:|:---:| 

4. Remove the empty PCB you used for alignment and spacing.
5. Check the correct alignment and contact pressure of the pogo pins by mounting the Boron directly on the programmer.

**Congratulations you successfully built the Boron ublox SARA-R4 Firmware Programmer!**

