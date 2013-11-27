ATtiny85Minimal
============

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
* The gerber files in the zip file ./ATtiny85Minimal/Gerber+brd_REV_1.0/ATtiny85Minimal.zip can be directly uploaded to OSHPark.com to order it.

