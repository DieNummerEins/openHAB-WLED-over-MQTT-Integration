# openHAB MQTT Based Integration of the WLED Project by Aircookie

This example configuration for openHAB integrates the WLED project made my Aircookie (https://github.com/Aircoookie/WLED)

This configuration is tailored for openHAB 2.5 with the embedded MQTT Broker and the MQTT 2.5 Binding. The used WLED version is 0.9.0.

Prerequites are as follows:
- openHAB 2.5
- MQTT Broker (it doesn't matter if you use the embedded Moquette or an external Broker like Mosquitto)
- Installed MQTT 2.5 Binding
- Working ESP8266 or ESP32 with WLED 0.9.0 or above flashed

Keep in mind, that at some point this example might not work as the WLED is discussing if they are going to change the mqtt topic structure.
By chance i will adapt this example for the coming changes, however i can't promise it.

For more information look at:
https://github.com/Aircoookie/WLED/issues/207

Also the original configuration and hopefully this example will be discussed at the openHAB community forum in this thread:
https://community.openhab.org/t/solved-wled-please-make-this-work-in-openhab/82783/28