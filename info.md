![Logo](https://raw.githubusercontent.com/AaronDavidSchneider/SonosAlarm/master/logo%402x.png)

# Sonos Alarm

Custom component for Home Assistant to control your SONOS Alarm

![Example](https://raw.githubusercontent.com/AaronDavidSchneider/SonosAlarm/master/example.png)

**Features:**

- Switch your alarms on/off
- no configuration needed
- information about you alarms, like time, volume, etc in attributes

## Installation

**Install via HACS**
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)
The custom component is available via [HACS](https://github.com/custom-components/hacs)

**Manual Install**

If you want to install the custom commponent manually, add the folder `sonos_alarm/` to `YOUR_CONFIG_DIR/custom_components/`.

## Configuration
**As Integration:**

Go to the `Integrations pane` on your Home Assistant instance and search for `Sonos Alarm`.

## Exposed entities

- `switch.sonos_alarm_[id of your alarm]` for each of your SONOS Alarms

## Example Usage
Have a look at https://github.com/AaronDavidSchneider/SonosAlarmAutomation for automations using `sonos_alarm`
