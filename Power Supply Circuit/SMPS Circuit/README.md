# Power Supply Circuit Descreption

* Power supply circuit contains  different circuits to generate  diffrent voltage levels
  1. First circuit is a SMPS circuit takes 12V input and generates 5v output.  
* SMPS Circuit generates 5V using MP1584EN-LF-Z IC which is from Monolithic Power Systems.
* Why did I choose SMPS ?
* - Input - output difference is high (12V - 5V)
  - Output current is high.(3A)
  - SMPS have high efficiency at high current.
  - A switching regulator (SMPS) was used instead of a linear regulator due to the large voltage difference between 12V and 5V. Using a linear regulator would result in significant power dissipation and low efficiency. The SMPS solution improves efficiency and reduces thermal stress in the system.
* The SMPS circuit contains following features.
  1. Reverse polarity protection.
  2. Overvoltage protection.
  3. Surge protection .
* The power supply circuit also have a LED to notify whether system is powered or not.
* R26 and R31 resistors are responsible for connecting SMPS block with the entire circuitry.If we remove these two resistors ,SMPS section will completely isolate from the rest of the circuitry.
* Decoupling capacitors are placed to suppress the high frequency noise on both input and output side.
