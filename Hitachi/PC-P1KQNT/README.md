### Hardware
- ESP32 C3 Super Mini (or other ESPHome compatible device)
- RS-485 to TTL Conversion Module
- AMS1117 Based 5V Power Module (or other DC 12v to DC 5v Module)

### Register Chart

Resgister Address | Item | Resgister Value
----------------- | ---- | ---------------
0x00 | Current Temperature  | Celsius (Read Only)
0x20 | Power                | 0: OFF<br>1: ON
0x21 | Ventilate Mode       | 1: Auto<br>8: Heat Exchage<br>16: Normal
0x22 | Fan Speed            | 2: High<br>4: Low

### Reference
- https://github.com/yuhuachang/mt7688-rs485-webservices

