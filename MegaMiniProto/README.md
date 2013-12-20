MegaMiniProto
============

This is a shield for the last third of the Arduino Mega2560.

![Board](https://raw.github.com/TMuel1123/MiniProjects/master/MegaMiniProto/img.png)

* It covers the pins 14-53 and A8-A15. These pins include USART 1-3 (14-19), I2C (20,21), PWM (44-46) and SPI (50-53).
* It still fits onto the Arduino Mega2560 if a normal shield ia connected to the Arduino Mega.
* The gerber files in the zip file ./Gerber+brd/MegaMiniProto.zip can be directly uploaded to OSHPark.com to order it.

Revision 1.1
------------
* Made the text more bold on the top and bottom silk screen. Now it has the eagle setting size 32mil ratio 12%. The ratio of 12% seems to be the minimum that can be cleanly printed

Revision 1.2
------------
* Fixed a horrible mistake. The holes of all vias on the board where 0.8mm so that pinheaders do not fit through the holes. I've enlarged the drills of the vias for the connection to the Arduino to 1.2mm and all other holes to 1.1mm. I also had to reduce the fontsize to 24mil to make it fit between the vias.
