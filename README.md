# OPNsense PON Metrics Plugin

A custom dashboard widget for OPNsense designed specifically for the **WAS-110 SFP ONT** running the **8311 community custom firmware**. 

This plugin provides real-time monitoring of optical health and ONT internals directly from your OPNsense dashboard, utilizing the custom API endpoint provided by the 8311 firmware.

## Compatibility
* **Hardware:** WAS-110 SFP ONT
* **Firmware:** 8311 v2.8.3 Custom Firmware (required for API access)

## Features
* **Customizable Dashboard:** Choose which metrics to display via widget settings.
* **Configuration Settings:** Settings page under the Reporting tab with options for your ONT IP (default 192.168.11.1) and temperature threshold for text highlighting.

## Installation
Install the plugin directly via the command line:

```bash
pkg add https://github.com/thespencire/pon-metrics/releases/download/v1.0.0/os-pon-metrics-1.0.pkg
