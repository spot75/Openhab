# esp8266 as homekit Thermometer for Openhab2


This is my first try to make a wireless thermometer for the homekit via Openhab.

It uses the edited 
You need to already have Openhab2 running with homekit intergration.

What you need:
1. esp8266 module
2. Openhab with homekit
3. The rules file to convert the string to number
4. The items file to connect to esp8266 web server.


First flash the code to esp8266 with arduino IDE.
Then test it in your web browser, you schould see e.g. only this "21,55" .
Then save the esp8266.items in your Openhab2 items directory and the temperature.rules to rules directory.

