Smart Home


⚙️ Working Principle

This system acts as a central hub for home automation. It uses an HC-05 Bluetooth Module to establish a wireless serial connection between an Android smartphone and the Arduino.

Voice Command: The user speaks into a mobile app (e.g., "Turn on light"). The app converts voice to text and sends it via Bluetooth.

Processing: The Arduino reads the incoming string of text character by character.

Action: The code looks for keywords (like "light on" or "temperature").

If a command matches, it triggers digital pins to turn LEDs on/off (simulating appliances).

If the "temperature" command is received, it reads the DHT11 sensor and sends the data back to the phone screen.

🔌 Hardware Used

Arduino UNO: The brain of the project.

HC-05 Bluetooth Module: Receives wireless data from the phone.

DHT11 Sensor: Measures ambient temperature and humidity.

LEDs (3x): Represent Home Appliances (Light, Fan, TV).

Resistors (220Ω): Protect the LEDs from burning out.

Jumper Wires & Power Source.

🚀 Future Plans

Real Appliance Control: Replace LEDs with Relay Modules to control actual 220V AC bulbs and fans.

Voice Feedback: Add a speaker so the house talks back (e.g., "Temperature is 25 degrees").

Internet Control (IoT): Upgrade from Bluetooth to Wi-Fi (ESP8266) to control the house from anywhere in the world.
