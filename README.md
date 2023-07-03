# SecureSense: A FoodMonitoringSystem

## What is the device?
a stand-alone IoT-based Food Quality Monitoring System

## How it works?
- it is a plug-and-play device with the code pre-flashed and ready to run
- it requires an appropriate power-source
- the ESP32Cam and the ESP32Board are pre-configured to connect to an AP (Wifi Hotspot) with SSID: "Internet" and password: "computer"
- the wifi credentials can be erased and reconfigured using the Wifi Manager
- a telegram bot is used to control the ESP32Cam

### ESP32Cam Functions
```bash
- /start
- /photo
- /caption
- /flashphoto
- /entim
- /distim
- /1-1440 minutes
- /status
- /reset
- /reboot
```
