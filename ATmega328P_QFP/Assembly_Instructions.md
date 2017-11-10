# Assembly Instructions

1. Clean PCB, stencil, jig, and tools with IPA
2. Place PCB into jig, and tape the jig together
3. Aligne the stencil with the PCB, and firmly tape the stencil onto the jig
4. Lightly tape the jig onto the table
5. Put a blop of solder paste onto the stencil near the slots for the 328p
6. Use the solder paste spreader to spread the blob of solder paste over the sentencil. Start by bring the paste over the 328p slots and then move outward on the sentencil to the other components
7. Remove the stencil from the jig
   * Be carful not to smear the paste during this process
8. Remove the jig from around the PCB
9. Use exacto knife and dental picks to clean up solder paste
   * Try to get a little bit of seperation between the solder paste on each pad
   * Make sure the solder paste isn't going to flow onto an vias or holes
   * It dosen't have to be perfect. The solder sheild on the purple portions of the PCB will cause the paste to flow to the copper when the paste is liquified in the oven
10. Place the 328p chip on the PCB
    * The white dot on the PCB corosponds to a dot on the 328p chip
11. Place the osicllator chip on the board. Be carful that it does not touch a pin on the microcontroller
    * Orientation does not matter on this component
12. Place the 0.1uF capacitor that is closest to the microcontroller, then place the rest of the 0.1uF capacitors
    * Orientation does not mater on these components
13. Place the 10kΩ and 330Ω resistors
    * Orientation does not mater on these components
14. Place the green LED
    * The green triangle on the bottom of the LED should aline with the triangle printed on the PCB
15. Place the 10uF capacitor
    * The dark line on the top of the capcitor should aline with the curved line on the PCB
16. Place board into the solder reflow oven, and run it
17. Remove board from the oven when it's cool
18. Visual inspect the board for shorts and bad connections
19. Use DMM to check for shorts between VCC and GND
    * To do this turn the DMM to messure restance and make sure the resistance is large
20. Use DMM to check for shorts between VCC and all other pins
    * Keep in mind that RST is pulled up, so there should only be 10kΩ between it and VCC
21. Use DMM to check for shorts between GND and all other pins
22. Hand solder header pins onto the board