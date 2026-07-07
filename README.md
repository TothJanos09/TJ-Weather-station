A solar powered weather station

Part list:
- Seeed Studio XIAO ESP32-C6
- 6V 5W solar panel
- BQ24650-based MPPT module
- 1S 4P LiFePO4 battery pack (4× 18650 1600mAh = 6400mAh)
- 1S LiFePO4 BMS
- MT3608 boost converter 
- VEML7700 — ambient light 
- AS7331 — UV A/B/C  — custom ESPHome component
- AHT20+BMP280 combo board — temperature, humidity, pressure
- XKC-Y25-V — capacitive rain sensor
- PCF8574 — I2C GPIO expander reading XKC signal

- Using Home Assistant and the built in EspHome manager
