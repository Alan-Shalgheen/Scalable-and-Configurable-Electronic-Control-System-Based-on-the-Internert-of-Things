## Notes on Development

This documentation highlights the main features and functional units of the system, while intentionally omitting certain personal caveats and proprietary details.

<Transformer Reverse Engineering>
Since no datasheet was available for the off‑shelf transformer, I reverse‑engineered it to fit the design requirements. To support this, I built a custom inductance meter using an Arduino.

<DIY Programming Tools>
I developed a custom SPI AVR programmer and integrated it into Atmel Studio 7.0, ensuring reliable programming without relying on commercial tools.

<Design Without Laboratory Access>
Due to the absence of a laboratory setup, the project was first designed theoretically and later validated in practice. Despite this constraint, the system ran successfully with no major issues reported.

<Level Shifter Limitation>
  The only malfunction encountered was with the level shifter IC between the ESP32 and AVR MCU, which proved unsuitable for UART protocol usage. This was documented as a design caveat for future iterations.
