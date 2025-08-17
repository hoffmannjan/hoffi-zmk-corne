# Configuration files for ZMK firmware

This directory contains the configuration files for the Corne Wireless split keyboard.

The setup uses **BLE master/slave mode**, as defined by the `corne_left` and `corne_right` shields:
- left half  as central (master),
- right half as peripheral (slave),
- both halves using nice!view OLEDs.

The setup is designed for a consistent and descriptive BLE name:  `FullMetalCorne`
This name can be customized via `CONFIG_ZMK_KEYBOARD_NAME` in the config.

# Config editor

To edit this config I use [nickcoutsos editor](https://nickcoutsos.github.io/keymap-editor/).
