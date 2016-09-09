# The GNU Little Wire

This design is a special version of Ihsan Kehribar's USB multi-tool, [Little Wire](http://littlewire.cc/), made for
the [2016 GNU Tools Cauldron](https://gcc.gnu.org/wiki/cauldron2016).

Uses include:

* usbtinyisp compatible AVR programmer.
* 4 channel GPIO.
* ADC with 10 bit resolution.
* 2 parallel hardware PWM outputs.
* SPI interface.
* I2C interface.
* 1-Wire interface
* WS2812 RGB LED interface.
* Multiple device support.

The PCB design was created by [Bolport](http://boldport.com/), using [PCBmodE](https://github.com/boldport/pcbmode).

## Programming

The kits that delegates at the 2016 GNU Tools Cauldron received have already been programmed with the [micronucleus
ATtiny USB bootloader](https://github.com/micronucleus/micronucleus), removing the need for an AVR ISP.

The micronucelus commandline is required in order to load application firmware, e.g. the [Little Wire or CDC-232 firmware](http://littlewire.cc/downloads.html).

The board can also be programmed via the Arduino IDE and is compatible with the [DigiStump Digispark](https://digistump.com/wiki/digispark/tutorials/connecting).

## Licence

The GNU Little Wire design is copyright 2016 Embecosm Ltd and provided under the GFDL v1.3 & CC BY-SA 2.0.
