## Radio

RFD900x-US Telemetry Bundle (FCC approved)

* 2 modems (one for plane, one for laptop)
* antennas (will use these for the laptop, but will use [separately purchased antennas](radioantenna.md) for the plane)
* cables

This radio is not really needed if the drone is always within line-of-site?

The drone can be controlled via laptop with this radio modem. You can also view telemetry data on the laptop. (Alternatively, control can be taken over by a transmitter which is bound to an on-board receiver.)

"These modems are high-power RF devices and it is recommended to power these devices from a separate power supply and not directly from the Flight Controller or USB"

* Current Consumption TX mode: ~1A peak at +30dBm
* Current Consumption RX mode: 60mA (typical)

The [manual is here](http://files.rfdesign.com.au/Files/documents/RFD900x%20DataSheet%20V1.1.pdf).

"The FCC limit for EIRP is 4 Watts, or 36dBm for frequency hopping radios in the ISM 900 MHz band. The Australian EIRP limit is 30dBm as defined by ACMA."

More info [on RFD900](https://ardupilot.org/plane/docs/common-rfd900.html) and [on telemetry port setup](https://ardupilot.org/plane/docs/common-telemetry-port-setup.html)

"Telem1 (aka Serial1) is for MAVLink communication and supports flow control. This should be used especially for high power devices (up to 1 amp) But NOT the RFD900 telemetry radio"
