# esphome-modbus-master
Modbus master using esphome on wt32-eth01 board and max3485

In this project I created a custom device running esphome on a [WT32-ETH01](https://github.com/ldijkman/WT32-ETH01-LAN-8720-RJ45-) board connected to [max3485](https://www.analog.com/en/products/max3485.html) to cotrol multiple modbus devices. 
A logic-level converter was added to allow readings from a 5V pulse ABB meter as well.

Future improvments will include I2C GPIO extender and a screen.

**Current modbus devices implemented:**

- Dixell HVAC controller (XR series)
- ABB B24 Electricity Meter
- ABB Pulse Electricity Meter
- CHINT DTSU666 Electricity Meter
- Vision Battery Pack
- BSL-BAT Battery Pack
- Tibbo Temperature Probe

![Image of the device](/image.jpg)
