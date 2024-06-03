# Water Quality Monitoring with Oxilife and RPI PicoW

## Description

This project reads water quality and treatment parameters from an Oxilife device using Modbus communication protocol and transfers the data to an RPI PicoW. The data is then integrated into the Home Assistant ESPhome environment for monitoring and automation. Additionaly I added a DHT20 sensor to read temperature and humidity in the pool house.

![image](https://github.com/bartvdg/ESPHome-Oxilife/assets/44372484/49247495-76a0-4ffc-9ff6-40b7a224e3f1)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

### Prerequisites

- RPI PicoW
- Grove RS-485
- Oxilife device
- Home Assistant
- ESPhome

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/bartvdg/ESPHome-Oxilife.git
