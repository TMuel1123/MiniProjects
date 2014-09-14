MiniProjects
============

This repository contains various mini projects where it would be to much to make a own repository for each project.

ATtiny85Minimal
-------------------------

This board was just a test of the order peocedure at OSH Park. It is a simple board which contains an ATtiny85 a button and a LED.

<pre>
// ATMEL ATTINY45 / ARDUINO
//
//                          +-\/-+
// (Reset) Ain0 (D 5) PB5  1|    |8  Vcc
//         Ain3 (D 3) PB3  2|    |7  PB2 (D 2) Ain1 (SCK)
//         Ain2 (D 4) PB4  3|    |6  PB1 (D 1) pwm1 (MISO)
//                    GND  4|    |5  PB0 (D 0) pwm0 (MOSI) INT0
//                          +----+
</pre>

![Board](https://raw.github.com/TMuel1123/MiniProjects/master/ATtiny85Minimal/img.png)

* Bread board friendly
* Push button is connected to D0 which is INT0
* Has a LED connected to D1 which is a PWM output
* The gerber files in the zip file ./ATtiny85Minimal/Gerber+brd/ATtiny85Minimal.zip can be directly uploaded to OSHPark.com to order it.

MegaMiniProto
-------------------------

This is a shield for the last third of the Arduino Mega2560.

![Board](https://raw.github.com/TMuel1123/MiniProjects/master/MegaMiniProto/img.png)

* It covers the pins 14-53 and A8-A15. These pins include USART 1-3 (14-19), I2C (20,21), PWM (44-46) and SPI (50-53).
* It still fits onto the Arduino Mega2560 if a normal shield ia connected to the Arduino Mega.
* The gerber files in the zip file ./Gerber+brd/MegaMiniProto.zip can be directly uploaded to OSHPark.com to order it.


3x_74HC595
-------------------------

This board contains three 74HC595 shift registers

![Board](https://raw.github.com/TMuel1123/MiniProjects/master/3x_74hc595/img.png)

* Bread board friendly
* the boards can be chained together
* The gerber files in the zip file ./3x_74HC595/Gerbers/3x_74HC595.zip can be directly uploaded to OSHPark.com to order it.
