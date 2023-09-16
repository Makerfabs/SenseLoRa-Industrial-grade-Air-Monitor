# SenseLoRa Industrial grade Air Monitor

```c++
/*
Version:		V1.0
Author:			Vincent
Create Date:	2023/9/16
Note:

*/
```
# Makerfabs

[Makerfabs home page](https://www.makerfabs.com/)

[Makerfabs Wiki](https://wiki.makerfabs.com/)

# How To Use

## Arduino Complier Option

**If you have any questions，such as how to install the development board, how to download the code, how to install the library. Please refer to :[Makerfabs_FAQ](https://github.com/Makerfabs/Makerfabs_FAQ)**

- Install board : ESP32 Version 2.0.11
- Select "ESP32-S3"
- Select Erase All Flash
- Upload codes

Arduino libraries:

- RadioLib 4.6.0
- Adafruit_Unified_Sensor 1.1.9
- Adafruit_AHT10 0.1.0
- Adafruit_BusIO 1.14.1
- Adafruit_SGP30_Sensor 2.0.0
- BH1750 1.3.0


## Lora Data Format

```json

{
	"ID": "AirM01",
	"COUNT": 22,
	"SLEEP": 3600,
	"bat": 3.48,
	"temp": 0.00,
	"humi": 0.00,
	"eco2": 0.00,
	"lux": 0.00
}

 ```