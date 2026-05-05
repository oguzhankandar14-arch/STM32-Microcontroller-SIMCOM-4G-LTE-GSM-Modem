- ## USB - UART CONVERTER

- A USB-to-UART interface is implemented using a USB Micro-B connector and a CP2102 bridge controller. 

- The CP2102 converts USB signals to UART, allowing the system to communicate with a PC via a virtual COM port. ESD protection is added on the USB lines to ensure reliability.
- The reset (RST) pin is connected to 3.3V through a 4.7kΩ pull-up resistor to ensure a stable default state. 
- Decoupling capacitor are placed to suppress high frequency noise.
