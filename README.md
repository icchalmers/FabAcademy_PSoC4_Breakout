# FabAcademy_PSoC4_Breakout

A small breakout board for the PSoC 4 CY8CKIT-049 42xx prototyping kit. It includes WS2812b LEDs, a TMP275 temperature sensor, CapSense buttons and a header to attach an ESP-01 module. It was made as part [Fab Academy 2015](http://www.fabacademy.org/) at [Fab Lab Strathclyde](http://www.strath.ac.uk/fablab/). You can follow the process on [my class website](http://fabacademy.org/archives/2015/eu/students/chalmers.iain/index.html). The content is also mirrored to [my GitHub Pages site](http://icchalmers.github.io/).

Note that there us one jumper wire needed if making this as a single sided board.

# WARNING!

This board runs at 3.3V. You MUST modify the USB-UART board that comes with the kit or bad things will happen! The simplest option is to remove the fuse on VUSB and power everything from the board. More options are discussed on my class webpage.
