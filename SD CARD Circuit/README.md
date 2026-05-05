## SD Card Circuit

The SD card interface is designed to support reliable data storage and communication with the microcontroller while ensuring proper signal integrity and protection.

The SD card holder is connected using standard SDIO signals, including CMD, CLK, DATA lines, and power supply. Decoupling capacitors (100 nF and 10 µF) are placed close to the power pins to ensure stable operation and reduce supply noise.

### ESD Protection
Each signal line is protected using ESD diodes to prevent damage from electrostatic discharge. This is especially important since SD cards are externally accessible components.

### Signal Integrity and Filtering
A series resistor (22Ω) is used on the clock line to reduce signal ringing and improve signal integrity. This helps ensure reliable high-speed communication between the microcontroller and the SD card.

The overall design focuses on robustness, protection, and stable high-speed data communication.

