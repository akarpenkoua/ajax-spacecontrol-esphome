# ajax-spacecontrol-esphome
Ajax security managed by esphome esp32 device

The objective was to manage Ajax security (https://ajax.systems/)  from Home assistant https://www.home-assistant.io/

I used community based addon to monitor system status via SIA
and discribed in the post hardware soldering 
https://community.home-assistant.io/t/ajax-alarm-system/62853/99

Board used - ESP32 wroom v1 as I had one
https://www.espressif.com/en/products/devkits/esp32-devkitc/overview

Here is the code for ESPHOME (esphome.io)
https://github.com/akarpenkoua/ajax-spacecontrol-esphome/blob/master/esphome_config

Here is simple automation that syncronises SIA with "virtual alarm panel in HA"
https://github.com/akarpenkoua/ajax-spacecontrol-esphome/blob/master/homeassistant-automations
