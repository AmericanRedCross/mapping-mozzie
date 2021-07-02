# BEC #
The Battery Eliminator Circuits regulate the battery voltage to 5V while allowing sufficient current to power the servos, Raspberry Pi, and RFD900x.

Qty 2

Primary: [Hobby King](https://hobbyking.com/en_us/turnigy-5a-8-26v-sbec-for-lipo.html)

Alternative: [original mozzie UBEC](http://www.banggood.com/ZTW-10A-BEC-UBEC-Universal-Battery-Eliminator-Circuit-For-RC-Models-p-989402.html?p=U4150312300081201707)

The Raspberry Pi, RFD900x and servos should not get power thru the Pixhawk because they can draw too much current.

* The BECs have 5A max continuous output current.
* The RFD900x has ~1A peak consumption, and
* the Raspberry Pi [can draw 3A](https://www.raspberrypi.org/documentation/hardware/raspberrypi/power/). Raspberry Pi bare-board active current consumption is 600mA. The BEC can [power the Raspberry Pi](https://magpi.raspberrypi.org/articles/power-supply) via GPIO pins \#4 (5v Power) and \#6 (Ground). Pin map [here](https://pinout.xyz/pinout/pin2_5v_power#).


The pixhawk will get power from the PM02. It can get backup power from the RFD900 BEC. It can get a second backup power source thru the Rasberry Pi. The maximum total USB peripheral current draw for the RPi is 1.2A (per link above), while the [Pixhawk could draw 0.5A (at 5V)](https://diydrones.com/profiles/blogs/pixhawk-and-apm-power-consumption)).

[BEC reference info](https://oscarliang.com/what-is-esc-ubec-bec-quadcopter/)
