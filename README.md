
This is my configuration using the open-sourced [Home Assistant](https://home-assistant.io/). This allows automation control over most of my house. It also allows secure remote access for control while away. Almost every device can be controlled locally, so if internet connection is lost, everything is still able to communicate properly.


# My Setup:

Everything is powered by a Dell T30 server with an Intel Xeon E3-1225 v5 chip and 8 GB of RAM. Unraid is the host OS while Home Assistant is running in Docker. I am also running a seperate version of Hass.io on a VM. I initially started with Home Assistant before Hass.io was available. The intent is to eventually move everything to Hass.io.

I am running Home Assistant Version __0.103.4__

### Additional Hardware:
* Philips Hue Hub
* Broadlink RM Pro+
* GoControl HUSBZB-1
* Logitech Harmony Hub

# Integrated Devices

#### Z-Wave Controlled Devices
* [GE Z-Wave Plus Smart Switch](https://www.amazon.com/GE-Repeater-Extender-SmartThings-14291/dp/B01M1AHC3R/)
* [GE Z-Wave Plus Smart Dimmer](https://www.amazon.com/GE-Enbrighten-Repeater-SmartThings-14294/dp/B01MUCZA1C/)
* [GE Z-Wave Plus Outside Smart Plug](https://www.amazon.com/GE-Weather-Resistant-Required-Works-SmartThings-14284/dp/B06W9NWFM3/)
* [Schalge Z-Wave Touchscreen Deadbolt Lock](https://www.amazon.com/Schlage-FE469NX-ACC-716-CAM/dp/B00D1M5YTG/)

#### Philips Hue Devices
* [Hue White and Color Ambiance Bulbs](https://www.amazon.com/Philips-464487-Equivalent-Compatible-Assistant/dp/B01M9AU8MB/)
* [Hue White and Color Ambiance Lightstrip](https://www.amazon.com/Philips-Ambiance-LightStrip-Compatible-Assistant/dp/B0167H33DU/)

#### RF Controlled Devices
* Bedroom Ceiling Fan and Light
* [Rollerhouse Battery Roller Motor](https://www.amazon.com/Internal-Re-Chargeable-Automatic-Motorized-Compatible/dp/B07RWTYDXG/)

#### Wifi Devices
* [Harmony Hub](https://www.amazon.com/dp/B00BQ5RYI4/)
* [Broadlink RM Pro+](https://www.amazon.com/BroadLink-Automation-Universal-Compatible-Smartphones/dp/B0742CXGHY/)
* [Ring Pro Doorbell](https://www.amazon.com/Ring-Doorbell-Activated-Installation-existing/dp/B01DM6BDA4/)
* [Wyze Camera](https://www.amazon.com/dp/B076H3SRXG/)
* [Unifi G3 Flex Camera](https://www.amazon.com/Ubiquiti-Indoor-Outdoor-Camera-UVC-G3-FLEX/dp/B07D6MHK7S/)
* [Chamberlain MyQ Garage Door](https://www.amazon.com/Smart-Garage-Opener-Chamberlain-MYQ-G0301/dp/B075H7Z5L8/)
* [Generic Smart Plugs with Energy Monitoring Flashed with ESPHome](https://www.amazon.com/gp/product/B07LGSBFNJ/)
* [TP-Link Kasa Smart Plugs](https://www.amazon.com/dp/B01K1JVZOE/)
* [WS2811 LED Strips with WLED Flashed ESP8266](https://www.amazon.com/gp/product/B01CNL6LBK/)
* [Ecovacs Deebot N79S Vacuum](https://www.amazon.com/gp/product/B077HW9XM7/)
* [Ecobee3 Lite Thermostat](https://www.amazon.com/ecobee3-lite-Smart-Thermostat-Black/dp/B06W56TBLN/)
* [Amazon Echo](https://www.amazon.com/gp/product/B0749WVS7J/)
* [Amazon Echo Dot](https://www.amazon.com/gp/product/B07PDHSLM6/)
* [Amazon Echo Show 5](https://www.amazon.com/gp/product/B07HZLHPKP/)

# Automation Highlights

## NHL Goal Light
Using the NHL's open API as automation triggers, I recreate the stadium feel with flashing lights and sounds for Blackhawks goals, oppenent goals, intermission, and game start.

## Room Based Alexa Voice Control
With the limited Harmony Hub integration into Amazon Alexa, these automations are able to see which echo device was last activated to determine which device should be changed.

## Position Specific RF Controlled Blinds
The available controls for the motorized blinds are up, down, and stop. The automations are able to store the blinds position and allow it to be set to certain position.

# Dashboards

## Main

### Light

![Main](/dashboard/Main.png)

### Dark

![Main Dark](/dashboard/Main%20-%20Dark.png)

## Downstairs

### Light

![Living Room](/dashboard/Living%20Room.png)

### Dark

![Living Room Dark](/dashboard/Living%20Room%20-%20Dark.png)

## Master Bedroom

### Light

![Master Bedroom](/dashboard/Master%20Bedroom.png)

### Dark

![Master Bedroom Dark](/dashboard/Master%20Bedroom%20-%20Dark.png)

## Music

### Light

![Music](/dashboard/Music.png)

### Dark

![Music Dark](/dashboard/Music%20-%20Dark.png)

## Alarm Panel

### Light

![Alarm Panel](/dashboard/Alarm%20Panel.png)

### Dark

![Alarm Panel Dark](/dashboard/Alarm%20Panel%20-%20Dark.png)

## Bedrooms

### Light

![Bedrooms](/dashboard/Bedrooms.png)

### Dark

![Bedrooms Dark](/dashboard/Bedrooms%20-%20Dark.png)

## Utilities

### Light

![Utilities](/dashboard/Utilities.png)

### Dark

![Utilities Dark](/dashboard/Utilities%20-%20Dark.png)