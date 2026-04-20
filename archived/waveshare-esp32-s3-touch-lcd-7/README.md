# Waveshare ESP32-S3 Touch LCD 7"

7-inch touch LCD panel with ESP32-S3, running ESPHome and LVGL for home automation and sensor displays.

![Waveshare ESP32-S3 Touch LCD 7](../../images/waveshare-esp32-s3-touch-lcd-7.jpg)

## Configuration

- **Template**: [esphome.yaml](esphome.yaml) — use the **contents of this file as your ESPHome config** in the dashboard or CLI (create or edit your device config so it matches this file).

## Where to Buy

- **Panel**: [AliExpress](https://s.click.aliexpress.com/e/_c37ljk8J) (~£40)

## Stand

- **Desk stand** (3D printable): [MakerWorld](https://makerworld.com/en/models/1009516-desk-stand-for-7inch-waveshare-touch-screen#profileId-2439605)

## Folder Structure

```
waveshare-esp32-s3-touch-lcd-7/
├── addon/          # Time, network, backlight
├── assets/         # Fonts and icons
├── device/         # device.yaml, sensors.yaml, lvgl.yaml
├── theme/          # Button and UI styling
├── esphome.yaml    # ESPHome config template
```

Customize for your setup by editing the YAML files under `device/`, `addon/`, and `theme/`. See the [main README](../../README.md) for full quick start and ESPHome setup.
