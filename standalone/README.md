## Standalone controllers

The information in this section applies to the following controllers:

- Densha de GO! Plug and Play

This controller is different from traditional controllers in the sense that it contains the game (an improved version of Densha de GO! Final) and does not connect to a PC or console. Externally, it looks similar to a TCPP-20009, except it does not include a pedal connection. Internally, it contains an ARM board running Linux. It requires a micro USB cable for power and a HDMI cable for video output.

The micro USB port supports USB OTG with a powered adapter and is used by Taito to install software updates.

It is possible to update the Linux kernel on the board to enable USB gadget mode and emulate traditional controllers, such as the DGOC-44U. This makes it possible to control other software. You can find more information [here](https://github.com/GMMan/dengo-plug-and-play-controller).

## Acknowledgements

Big thanks to [GMMan](https://github.com/GMMan), who has done research on this controller and developed several software modifications.
