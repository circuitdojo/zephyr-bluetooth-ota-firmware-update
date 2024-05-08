# Bluetooth OTA

## Instructions

1. Compile once and flash to your device. By default we're using the Zephyr signing key for MCUboot
2. Do a clean build
3. Copy your `build/zephyr/app_update.bin` to your phone
4. Use nRF Connect (for iOS or Android) to connect to your device
5. Navigate to the DFU menu

## Useful Links:

- [Nordic Tutorial](https://devzone.nordicsemi.com/guides/nrf-connect-sdk-guides/b/software/posts/ncs-dfu#dfu_over_bluetooth) (slightly out of date as of 5/8/24)
- [Video on HCI BLE on nRF91x](https://www.youtube.com/live/nDd3w9T5sMs?si=MTEtx2Qrmsa_lza5)
