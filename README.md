# ESP MQTT JSON Multisensor

Many thanks to Bruh Automatiotion for the start of this code as this just a hack together project using his project as a starting off point. 
https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor

The code covered in this repository utilizies Home Assistant's [MQTT Sensor Component](https://home-assistant.io/components/sensor.mqtt/), and a [NodeMCU ESP8266](http://geni.us/cpmi) development board. 

### Supported Features Include
- **SHT31** temperature sensor
- **SHT31** humidity sensor
- **TSL2561** light sensor
- **AM312** PIR motion sensor
- **Over-the-Air (OTA)** upload from the ArduinoIDE


#### OTA Uploading
This code also supports remote uploading to the ESP8266 using Arduino's OTA library. To utilize this, you'll need to first upload the sketch using the traditional USB method. However, if you need to update your code after that, your WIFI-connected ESP chip should show up as an option under Tools -> Port -> Porch at your.ip.address.xxx. More information on OTA uploading can be found [here](http://esp8266.github.io/Arduino/versions/2.0.0/doc/ota_updates/ota_updates.html). Note: You cannot access the serial monitor over WIFI at this point.  


### Parts List

**Amazon Prime (fast shipping)**
- [NodeMCU 1.0](https://amzn.to/2F8DBcB)
- [SHT31 Module](https://amzn.to/2MdfCNE)
- [TSL2561 Module](https://amzn.to/2Melia6)
- [Power Supply](https://amzn.to/2viBSzl)
- [Header Wires](https://amzn.to/2MaCcX1)
- [AM312 Mini PIR Sensor](https://amzn.to/2vxadcT)

