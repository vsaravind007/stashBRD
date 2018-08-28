# stashBRD
An ESP8266 based minimal IoT board with 20 digital I/O &amp; 1 ADC Channel.

**Features**
- 20 Digital I/O Pins
- 1 ADC Channel
- Integrated 3.3v Regulator
- Flash &amp; Reset Buttons
- Minimal Board Design

**Why?**

Almost all available ESP8266 based development boards are limited in digital I/O pins. Using an IO expander is the only way to add more IO pins to the chip. This board integrates the MCP23S17 IO expander with the ESP8266-12E module.

**Software**

Works with the MCP23S17 Arduino library: https://github.com/n0mjs710/MCP23S17 or write custom IO handling with the standard Arduino SPI library.

**BOM**

- ESP-12E Module x 1
- MCP23S17 IO Expander IC x 1
- AMS117 Voltage Regulator x 1
- 10uF Cap x 1
- 47uF Cap x 1
- 10k Resistor x 2
- 1x16 Male/Female Headers x 1
- 1x5 Male/Female Headers x 1
- 1x2 Male/Female Headers x 3
- 1x3 Male/Female Headers x 1
- Momentary Push Button x 2
