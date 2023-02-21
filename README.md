# ESPHome Configuration for the AirGradient DIY Pro
This is an example of ESPHome Configuration for the [Airgradient DIY Pro](https://www.airgradient.com/open-airgradient/instructions/diy-pro/), with the SGP30 TVOC sensor added.

It displays the sensor data on the onbaord OLED screen, and exposes the data via [ESPHome's native API](https://esphome.io/components/api.html)

The following secrets are used for configuration:
| Name         | Description     |
|--------------|-----------------|
| wifi_ssid    | Name of WiFi SSID to connect to |
| wifi_password | Password to wifi network |
| fallback_wifi_password | Password to the fallback WiFi network the device will create if it cannot connect to the specified WiFi network |
| ota_password | Password used for OTA updates |
