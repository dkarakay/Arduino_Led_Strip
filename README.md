# Arduino_Led_Strip

Hello. I have controlled a Led strip with Arduino. You can make it very easily.

    Arduino Uno or any kind of Arduino
    RGB Led Strip (I use 1 m)
    12V 1A Adapter
    ULN2003A or 3xBD679 NPN or 3xNPN (TIP 120)
    Breadboard with enough jumpers

First you have to buy all these stuff. RGB Led strip has 4 output cables(Red,Green,Blue and 12V Positive).

    With ULN2003A pin 1 is for Digital 9 pin, pin 2 is for Digital 10 pin, and pin 3 is for Digital 11 pin. You have to connect leds pins to 16,15,14(R,G,B). Pin 10 is for the Ground.
    With BD679 number 1 is for Arduino with 10K resistor, number 2 is for Led and number 3 goes to ground.

I have made this from ULN2003A and BDN679. This is the code that I used.
