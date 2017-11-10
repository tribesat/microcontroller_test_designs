# ATmega328P Quad Flat Pack (QFP)

This board was designed by the Tribesat Project in 2016. The purpose of this design was to test our ability to manufacture a board with an ATmega328P in a quad flat pack package.

The ATmega328P is an 8-bit AVR microcontroller. More information about it can be found [here](http://www.microchip.com/wwwproducts/en/ATmega328P).

The board desgine is derivied from the [Sparkfun Arduino Pro Mini](https://learn.sparkfun.com/tutorials/using-the-arduino-pro-mini-33v). The main difference between that board and this one is the removal of the voltage regulator and physical reset button. The pin out on this board is the same as the Arduino Pro Mini pin out.

This design can work with a 8Mhz or 16Mhz oscillator. If 16Mhz is used power the board at 5V, if 8Mhz is used the board may be powered at 3.3V.

Power must be regulated before entering into this board.

To reset the board, briefly short one of the RST pins to ground. The RST pins are  pulled high with a 10k resistor.

A green LED is connected to pin 13 for trouble shoting purposes. There is not power indicator LED.

The traces on the board are 0.01" and the vias have 0.02" drill holes. This is more than sufficient to handle the current through the traces. Right angles in the data traces have been avoided wherever possible.

The bottom and top layers of the board contain ground pours. These pores are connected through the GND pins and vias. These pores both insure good grounding in the board and isolate the oscillator from noise.

Decoupling capacitors were added as near to the chips as possible to minimize noise. This is detailed in the relevant data sheets.

0603 package size is used for all passive components. This size was selected because I believe it to be a good compromise between size and ease of placement.  The exception to this is the 10uF capacitor, which necessitated a larger package size.
