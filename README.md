# Inactivity Shutdown Windows
![Version](https://img.shields.io/github/package-json/v/EpicEmeraldPlayz/inactivity-shutdown-windows?color=yellow&cacheSeconds=2592000)
[![License: mit](https://img.shields.io/badge/License-MIT-red.svg)](https://github.com/EpicEmeraldPlayz/nodejs-inactivity-shutdown-windows/blob/master/LICENSE)

## About
The purpose of this project is to automatically shut down Windows based on CPU and network usage when it's below a certain threshold.

## Installation

```sh
npm install
```

## Usage

```sh
npm run start
```

## Configuration
- `trigger_interval` - Checking system usage every `x` seconds
- `average_interval_reset` - Reset system usage average every `x` seconds
- `trigger_shutdown_times` - Amount of times that meet requirements to trigger
- `trigger_shutdown_countdown` - Amount of time before shutdown
- `trigger_cpu_usage_target` - Maximum CPU percentage requirement
- `trigger_network_usage_target` - Maximum Network Transmitted & Received usage (Mbps) requirement
- `debug` - Enable debug messages in the console

## Author

👤 **Theerawat Patthawee**

* Github: [@ttwrpz](https://github.com/ttwrpz)

## 📝 License

Copyright © 2021 [Theerawat Patthwee](https://github.com/ttwrpz).

This project is [MIT](https://github.com/ttwrpz/nodejs-inactivity-shutdown-windows/blob/main/LICENSE) licensed.
