- STM32L073RZT6 is the brain of the system.It is low power MCU and also suitable for IoT applications.
- This circuit includes reset mechanism for microcontroller.
- The design includes two external crystal oscillators to meet both performance and low-power requirements. An 8 MHz crystal is used as the high-speed external clock (HSE) for the main system operation, ensuring stable and precise timing for the MCU and its peripherals.
In addition, a 32.768 kHz crystal is used as the low-speed external clock (LSE) for the RTC. This frequency is specifically chosen due to its binary compatibility (2¹⁵), allowing accurate timekeeping with minimal power consumption, especially in low-power modes.
- An 8-pin header is included in the design to provide access to the SWD (Serial Wire Debug) interface. This interface is used for programming and debugging the microcontroller during development and testing.
- This circuit includes 2 user input switch . RC filter is used to prevent debouncing effects of button.
- RGB LED circuit included for indication of serial communication.
- Decoupling capacitors are placed to suppress high frequency noise and provide sudden current requirement of MCU.
