# ESPHome remote server manager

With this ESPHome configuration you will be able to access the BIOS and terminal of the computer connected via UART over a serial TCP stream. At the same time basic things can be controlled and monitored remotely.

## Features

- Raw UART stream over TCP
  - Access via <NODE_NAME>.local:6638
  - Or access via <NODE_IP>:6638
- Webserver for control
  - Access via <NODE_NAME>.local:80
  - Or access via <NODE_IP>:80

These features are available when used in combination with the hardware of [this project](https://github.com/ruben-iteng/ODROID-H3-mITX-adapter)

- Remote UART terminal (e.g. BIOS access)
- 3x USB power control (turn on/off USB power)
- Button input
- 3x APA102 on board RGB LEDs (can be extended via header)
- PC power button control by ESP32 via optocoupler
- Always-on, powered by +5V_STBY
- Connected via Ethernet

## [Documentation](https://ruben-iteng.github.io/ESPHome-Remote-Server-Manager)
