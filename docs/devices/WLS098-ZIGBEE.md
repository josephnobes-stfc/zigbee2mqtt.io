---
title: "Tuya 8-Gang Wall Touch Switch Board"
description: "Integrate your Tuya WLS098-ZIGBEE 8 gang wall touch switch via Zigbee2MQTT with a zigbee gateway."
addedAt: 2024-03-01T08:00:00
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# Tuya WLS098-ZIGBEE

|     |     |
|-----|-----|
| Model | WLS098-ZIGBEE |
| Vendor | [Tuya](/supported-devices/#v=Tuya) |
| Description | 8 gang wall touch switch board |
| Exposes | switch (l1, l2, l3, l4, l5, l6, l7, l8), linkquality |
| Picture | ![Tuya WLS098-ZIGBEE](https://www.zigbee2mqtt.io/images/devices/WLS098-ZIGBEE.png) |

<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->
## Notes

### Pairing
Long press any button for 5 seconds until the LED indicator starts flashing rapidly to enter pairing mode.

### Endpoints
This device exposes 8 switches through endpoints l1-l8. Each switch can be controlled independently.
<!-- Notes END: Do not edit below this line -->


## Exposes

### Switch (l1 endpoint)
The current state of this switch is in the published state under the `state_l1` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l1": "ON"}`, `{"state_l1": "OFF"}` or `{"state_l1": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Switch (l2 endpoint)
The current state of this switch is in the published state under the `state_l2` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l2": "ON"}`, `{"state_l2": "OFF"}` or `{"state_l2": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Switch (l3 endpoint)
The current state of this switch is in the published state under the `state_l3` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l3": "ON"}`, `{"state_l3": "OFF"}` or `{"state_l3": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Switch (l4 endpoint)
The current state of this switch is in the published state under the `state_l4` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l4": "ON"}`, `{"state_l4": "OFF"}` or `{"state_l4": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Switch (l5 endpoint)
The current state of this switch is in the published state under the `state_l5` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l5": "ON"}`, `{"state_l5": "OFF"}` or `{"state_l5": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Switch (l6 endpoint)
The current state of this switch is in the published state under the `state_l6` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l6": "ON"}`, `{"state_l6": "OFF"}` or `{"state_l6": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Switch (l7 endpoint)
The current state of this switch is in the published state under the `state_l7` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l7": "ON"}`, `{"state_l7": "OFF"}` or `{"state_l7": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Switch (l8 endpoint)
The current state of this switch is in the published state under the `state_l8` property (value is `ON` or `OFF`).
To control this switch publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"state_l8": "ON"}`, `{"state_l8": "OFF"}` or `{"state_l8": "TOGGLE"}`.
It's not possible to read (`/get`) this value.

### Linkquality (numeric)
Link quality (signal strength).
Value can be found in the published state on the `linkquality` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `255`.
The unit of this value is `lqi`.