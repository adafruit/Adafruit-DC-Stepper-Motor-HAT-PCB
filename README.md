## Adafruit DC Stepper Motor HAT and Bonnet PCB
<a href="http://www.adafruit.com/products/2348"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

Let your robotic dreams come true with the new DC+Stepper Motor HAT from Adafruit. This Raspberry Pi add-on is perfect for any motion project as it can drive up to 4 DC or 2 Stepper motors with full PWM speed control.

Raspberry Pi and motors are not included. Works with any and all Raspberry Pi computers with 2x20 connection port.

Since the Raspberry Pi does not have a lot of PWM pins, we use a fully-dedicated PWM driver chip onboard to both control motor direction and speed. This chip handles all the motor and speed controls over I2C. Only two pins (SDA & SCL) are required to drive the multiple motors, and since it's I2C you can also connect any other I2C devices or HATs to the same pins.

In fact, you can even stack multiple Motor HATs, up to 32 of them, for controlling up to 64 stepper motors or 128 DC motors (or a mix of the two) - just remember to purchase and solder in a stacking header instead of the one we include.

Motors are controlled by TB6612 MOSFET drivers with 1.2A per channel current capability (you can draw up to 3A peak for approx 20ms at a time), a big improvement over L293D drivers and there are built-in flyback diodes as well.

PCB files for the Adafruit DC Stepper Motor Hat and Bonnet. The format is EagleCAD schematic and board layout
- https://www.adafruit.com/products/2348
- https://www.adafruit.com/product/4280

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional information.
