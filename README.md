# xiaomi_humidifier_hass
Integration of Xiaomi Humidifier into Home Assistant

Based on existing Xiaomi AirPurifier integration into Home Assistant

Usage:
Place both files to {homeassistant_config_directory}/custom_components/fan/

In Home Assistant configuration file:

fan:
  - platform: xiaomi_miio_humidifier \n
    name: Xiaomi Humidifier \n
    host: 192.168.x.x
    token: 'xxxxxxxxxxxxxxxxxxxx'
    
    

