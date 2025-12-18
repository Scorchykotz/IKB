# IKB Smartmeter Integration for Home Assistant

[![codecov](https://codecov.io/gh/DarwinsBuddy/WienerNetzeSmartmeter/branch/main/graph/badge.svg?token=ACYNOG1WFW)](https://codecov.io/gh/DarwinsBuddy/WienerNetzeSmartmeter)
![Tests](https://github.com/DarwinsBuddy/WienerNetzeSmartMeter/actions/workflows/test.yml/badge.svg)

![Hassfest](https://github.com/DarwinsBuddy/WienerNetzeSmartMeter/actions/workflows/hassfest.yml/badge.svg)
![Validate](https://github.com/DarwinsBuddy/WienerNetzeSmartMeter/actions/workflows/validate.yml/badge.svg)
![Release](https://github.com/DarwinsBuddy/WienerNetzeSmartMeter/actions/workflows/release.yml/badge.svg)

## About 

This repo contains a custom component for [Home Assistant](https://www.home-assistant.io) for exposing a sensor
providing information about a registered smart meter at [Innsbrucker Kommunalbetriebe (IKB)](https://www.ikb.at/).

## FAQs
[FAQs](https://github.com/DarwinsBuddy/WienerNetzeSmartmeter/discussions/19)

## Installation

### Manual

Copy `<project-dir>/custom_components/wnsm` into `<home-assistant-root>/config/custom_components`

### HACS
1. Search for `IKB Smart Meter` or `wnsm` in HACS
2. Install
3. ...
4. Profit!

## Configure

You can choose between ui configuration or manual (by adding your credentials to `configuration.yaml` and `secrets.yaml` resp.)
After successful configuration you can add sensors to your favourite dashboard, or even to your energy dashboard to track your total consumption.

### UI
<img src="./doc/wnsm1.png" alt="Settings" width="500"/>
<img src="./doc/wnsm2.png" alt="Integrations" width="500"/>
<img src="./doc/wnsm3.png" alt="Add Integration" width="500"/>
<img src="./doc/wnsm4.png" alt="Search for WienerNetze" width="500"/>
<img src="./doc/wnsm5.png" alt="Authenticate with your credentials" width="500"/>
<img src="./doc/wnsm6.png" alt="Observe that all your smartmeters got imported" width="500"/>

### Manual
See [Example configuration files](https://github.com/DarwinsBuddy/WienerNetzeSmartmeter/blob/main/example/configuration.yaml)
## Copyright

This integration uses the API of the IKB smart-meter portal.

