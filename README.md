# temperature_sensor
Utilizing a thermistor, the code in this repository takes pin readings from a thermistor and translates them into temperature readings in either Fahrenheit or Celcuis.
Depending on what this temperature reading is compared to the last temperature reading, a value is calculated that tells a servo for how long to pulse in order to move a physical arrow closer to the temperature to echo the reading given by the thermistor.
These temperature readings are then appended to a URL that is sent via a PUSH request to Adafruit's REST API and appear on my Adafruit dashboard.
