---
title: "TuYa SPM02 control via MQTT"
description: "Integrate your TuYa SPM02 via Zigbee2MQTT with whatever smart home infrastructure you are using without the vendor's bridge or gateway."
addedAt: 2023-08-01T15:13:29
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# TuYa SPM02

|     |     |
|-----|-----|
| Model | SPM02  |
| Vendor  | [TuYa](/supported-devices/#v=TuYa)  |
| Description | Smart energy monitor for 3P+N system |
| Exposes | voltage_X, voltage_Y, voltage_Z, power_X, power_Y, power_Z, current_X, current_Y, current_Z, energy, produced_energy, linkquality |
| Picture | ![TuYa SPM02](https://www.zigbee2mqtt.io/images/devices/SPM02.jpg) |


<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->


<!-- Notes END: Do not edit below this line -->



## Options
*[How to use device type specific configuration](../guide/configuration/devices-groups.md#specific-device-options)*

* `energy_precision`: Number of digits after decimal point for energy, takes into effect on next report of device. The value must be a number with a minimum value of `0` and with a with a maximum value of `3`

* `energy_calibration`: Calibrates the energy value (percentual offset), takes into effect on next report of device. The value must be a number.


## Exposes

### Voltage_X (numeric)
Measured electrical potential value (phase X).
Value can be found in the published state on the `voltage_X` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `V`.

### Voltage_Y (numeric)
Measured electrical potential value (phase Y).
Value can be found in the published state on the `voltage_Y` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `V`.

### Voltage_Z (numeric)
Measured electrical potential value (phase Z).
Value can be found in the published state on the `voltage_Z` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `V`.

### Power_X (numeric)
Instantaneous measured power (phase X).
Value can be found in the published state on the `power_X` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `W`.

### Power_Y (numeric)
Instantaneous measured power (phase Y).
Value can be found in the published state on the `power_Y` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `W`.

### Power_Z (numeric)
Instantaneous measured power (phase Z).
Value can be found in the published state on the `power_Z` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `W`.

### Current_X (numeric)
Instantaneous measured electrical current (phase X).
Value can be found in the published state on the `current_X` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `A`.

### Current_Y (numeric)
Instantaneous measured electrical current (phase Y).
Value can be found in the published state on the `current_Y` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `A`.

### Current_Z (numeric)
Instantaneous measured electrical current (phase Z).
Value can be found in the published state on the `current_Z` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `A`.

### Energy (numeric)
Total forward active energy.
Value can be found in the published state on the `energy` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `kWh`.

### Produced_energy (numeric)
Total reverse active energy.
Value can be found in the published state on the `produced_energy` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The unit of this value is `kWh`.

### Linkquality (numeric)
Link quality (signal strength).
Value can be found in the published state on the `linkquality` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `255`.
The unit of this value is `lqi`.

