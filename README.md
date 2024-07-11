# Hot Water temperature monitoring system using an ESP32 and LCD display. 


Here's a breakdown of how you can build a hot water temperature monitoring system using an ESP32 and LCD display, along with code examples and considerations:

Hardware Components

ESP32 Development Board: The brains of the operation, handling temperature sensing, data processing, and display control.
Waterproof DS18B20 Temperature Sensor: A reliable and accurate sensor designed for measuring temperatures in liquids.
I2C LCD Display (e.g., 16x2 or 20x4): To visually display the temperature readings.
Resistor (4.7kΩ): A pull-up resistor for the DS18B20 sensor.
Breadboard and Jumper Wires: For prototyping and connecting components.
Software Setup

Arduino IDE: Install the Arduino IDE and add the ESP32 board support.
Libraries:
DallasTemperature: For communicating with the DS18B20 sensor.
OneWire: Required for the DallasTemperature library.
LiquidCrystal_I2C: For controlling the I2C LCD display.
