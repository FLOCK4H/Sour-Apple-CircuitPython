# Hello!

The **Sour Apple** attack is a method, where we send fake BLE (**Bluetooth Low Energy**) advertisement packets, that pop up notifications on all nearby iOS devices.
This implementation is a port of [RapierXbox](https://github.com/RapierXbox/ESP32-Sour-Apple)'s work to CircuitPython, using lower-level "**_bleio**" module.

> [!CAUTION]
> This exploit may cause the device to crash, specifically versions of iOS below 17.2

## List of notifications

- Apple TV Setup
- Apple TV Pair
- Apple TV Configure
- Apple TV Audio Sync
- Homepod Setup
- Number Setup
