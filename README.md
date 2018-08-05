# home_assistant_config_v2

My configuration for the popular home automation platform [Home Assistant](https://www.home-assistant.io/)

Current devices include:
  - 433 Mhz sockets w/ [ESP8266-powered MQTT interface](https://github.com/adam-c-fox/esp8266_433mhz_transmitter)
  - Raspberry Pi running LIRC to control an EPSON EMP-TW700 via IR (interfaced with Home Assistant via MQTT)
  - Amazon Echo Dot gen. 2
  - ESP8266 MQTT sensor node w/ temperature, humidity and light level (TODO: PIR motion sensor)
  
Hosted in Docker on an old Sony Vaio laptop running Ubuntu 18.04, alongside some other services including:
  - [Portainer](https://portainer.io/) to manage Docker more easily
  - [Node-RED](https://nodered.org/) for easily designing automations
  - [Plex](https://www.plex.tv/) media server
  - [Transmission](https://transmissionbt.com/) BitTorrent client
  
Current interface status:

![Interface image](https://i.imgur.com/3QfKANv.png)
