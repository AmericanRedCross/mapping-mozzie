## Plane ESC

ZTW 40A Brushless ESC with BEC 3A/5V Speed Controller, with connector.

Available from [Amazon](https://www.amazon.com/ZTW-Brushless-Controller-Helicopter-Connector/dp/B07QNMQ5C3/)


Unlike the quad ESCs, this ESC has a BEC, so it acts as another source of 5V power (capable of 3A continuous). This will be used to power the servos since "Pixhawk series flight controllers do not provide power for the servo rail (the AUX servo rail is unpowered and is limited to 1A)."  I don't think I need to worry about the 1A limitation -- The plane ESC power flows to the servos via the [EXT-8P](flightcontroller.md), not through the pixhawk. The EXT-8P + pins are shared, power does not have to route through the 8 pin cable.
