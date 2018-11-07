# YAMPAMPER (Yet Another Messaging Protocol as an Mqtt wrappER) - ESP8266/ESP32 driver

A simple messaging protocol built on top of MQTT. It provides subscriber and publisher functionality. You need to have a 3rd party MQTT broker like Mosquitto or Mosca.

It's great for IoT devices like sensors to communicate with a central server.

## Configure the project

```
make menuconfig
```

A special "Yampamper Configuratino" menu is avialble. There you can configure the Wifi details.

## Example

See `main/main.c` for an example application.

## Build and Flash

Build the project and flash it to the board, then run monitor tool to view serial output:

```
make -j4 flash monitor
```

(To exit the serial monitor, type `Ctrl-]`.)

See the Getting Started Guide for full steps to configure and use ESP-IDF to build projects.
