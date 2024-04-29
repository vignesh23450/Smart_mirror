# Arduino Nano DHT11 OLED Display with Touch Sensor

This Arduino project utilizes an Arduino Nano, a DHT11 temperature and humidity sensor, an OLED display, and a touch sensor to display temperature and humidity readings on the OLED display and to control LED lights with the touch sensor.

## Components Used:
- Arduino Nano
- DHT11 Temperature and Humidity Sensor
- OLED Display (SSD1306)
- Touch Sensor
- LED Lights

## Wiring:
- DHT11:
  - Signal pin to D2
- OLED Display (SSD1306):
  - SDA pin to A4
  - SCL pin to A5
- Touch Sensor:
  - Signal pin to D3
- LED Lights:
  - Anode (+) pin to D13
  - Cathode (-) pin to GND

## Functionality:
- The temperature and humidity readings are displayed on the OLED display.
- Touching the touch sensor turns on the LED lights connected to pin D13.

## Arduino Code:
The Arduino code for this project is provided in the `arduino_code.ino` file.

## Usage:
1. Connect the components according to the wiring diagram.
2. Upload the provided Arduino code to the Arduino Nano.
3. Power up the Arduino Nano.
4. Touch the touch sensor to turn on the LED lights.
5. The temperature and humidity readings will be displayed on the OLED display.

