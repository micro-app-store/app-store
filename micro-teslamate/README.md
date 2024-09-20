# TeslaMate

A powerful, self-hosted data logger for your Tesla.

- Written in **[Elixir](https://elixir-lang.org/)**
- Data is stored in a **Postgres** database
- Visualization and data analysis with **Grafana**
- Vehicle data is published to a local **MQTT** Broker

## Documentation

The documentation is available at [https://docs.teslamate.org](https://docs.teslamate.org/)

## Features

**General**

- High precision drive data recording
- No additional vampire drain: the car will fall asleep as soon as possible
- Automatic address lookup
- Easy integration into Home Assistant (via MQTT)
- Easy integration into Node-Red & Telegram (via MQTT)
- Geo-fencing feature to create custom locations
- Supports multiple vehicles per Tesla Account
- Charge cost tracking
- Import from TeslaFi and tesla-apiscraper