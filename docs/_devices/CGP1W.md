---
manufacturer: Qingping
name: Cleargrass indoor weather station with Atmospheric pressure measurement
model: CGP1W
image: CGP1W.jpg
physical_description:
broadcasted_properties:
  - temperature
  - humidity
  - pressure
  - battery
  - rssi
broadcasted_property_notes:
  - property: battery
    note: For battery level, we do not have accurate periodicity information yet.
  - property: rssi
    note: >
      The RSSI sensor is disabled by default. You can enable the RSSI sensor by going to `configuration`, `integrations`, select `devices` on the BLE monitor integration tile and select your device. Click on the `+1 disabled entity` to show the disabled sensor and select the disabled entity. Finally, click on `Enable entity` to enable it. 
broadcast_rate:
active_scan:
encryption_key:
custom_firmware:
notes:
---