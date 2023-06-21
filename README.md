# uDFRobot_MultiGasSensor
This a Library was change from the original DFRobots libary to make it compatible with Micropython devices such as ESP32, ESP8266.

If want to know more about the library you can visit the [Original Repo](https://github.com/DFRobot/DFRobot_MultiGasSensor).



### The Pin Connections
DEVICES                   | VCC    | GROUND  | RX                  |         TX
--------------------- | :------: | :----------: | :--------------: | :-------
SENSORS                 |  VCCC | GROUND |         SCL         | SDA
ESP32/8266             |    3V    | GROUND | RX2(GPIO16)  | TX2(GPIO17)