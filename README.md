This Project's documentation shows only the main features and functional units of the system, but lacks most of the details for personal caveats. 
I reverse-engineered an off-shelf transformer that has no datasheet in order to make it fit the design. For this purpose I built an inductunce meter with an Arduino.
I made a DIY SPI AVR programmer and defined it in Atmel Studio 7.0.
No lavoratory set was available during the work, so all of the project was designed theoritically first then conducted with no major reported issues.
Only the level shifter IC between the ESP32 and AVR MCU malfunctioned because it does not fit UART protocol usage.
