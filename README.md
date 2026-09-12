# ESP32 DHT11 + ThingSpeak

This project uses an **ESP32** and **DHT11 sensor** to measure temperature and humidity and upload the data to **ThingSpeak** over Wi-Fi.

## Components

* ESP32 Development Board
* DHT11 Sensor
* Jumper Wires
* Wi-Fi Connection

## Connections

| DHT11 | ESP32  |
| ----- | ------ |
| VCC   | 3.3V   |
| DATA  | GPIO 4 |
| GND   | GND    |

## Libraries

* WiFi
* ThingSpeak
* DHT sensor library by Adafruit

## ThingSpeak Fields

* **Field 1:** Temperature (°C)
* **Field 2:** Humidity (%)

## Output

Sensor readings are displayed on the **Serial Monitor at 115200 baud** and uploaded to ThingSpeak every **15 seconds**.

## Future Scope

Add real-time graphs and a web/mobile dashboard for remote monitoring.
