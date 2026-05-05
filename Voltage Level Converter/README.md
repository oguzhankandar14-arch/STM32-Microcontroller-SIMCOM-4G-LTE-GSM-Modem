- ## Voltage Level Converter
- A voltage level converter is used to interface UART signals between the microcontroller and external devices operating at different logic levels. Since the microcontroller and the SIM7600E-H module may use different voltage domains, direct connection is not reliable and may cause signal integrity issues or damage to the devices.

- The level converter ensures proper logic level translation and robust communication.

- The design supports two communication paths: direct MCU-to-modem communication and communication via an external USB-to-TTL converter.

- 0Ω resistors are used as configurable links to select the active path, allowing flexible routing without PCB modifications.
