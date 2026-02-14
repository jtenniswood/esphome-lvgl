# Guition ESP32-S3 4848S040 (4.0")

4-inch touch LCD panel with ESP32-S3, running ESPHome and LVGL for home automation and sensor displays.

![Guition ESP32-S3 4848S040](guition-esp32-s3-4848s040.jpg)

## Configuration

- **Template**: [esphome/template.yaml](esphome/template.yaml) — use the **contents of this file as your ESPHome config** in the dashboard or CLI (create or edit your device config so it matches this file).

## Where to Buy

- **Panel**: [AliExpress](https://s.click.aliexpress.com/e/_c3sIhvBv) (~£16)

## Stand

- **Desktop stand** (3D printable): [MakerWorld](https://makerworld.com/en/models/2327976-touch-screen-desktop-stand-for-guition-4848s040#profileId-2543111)

## Folder Structure

```
guition-esp32-s3-4848s040/
├── addon/          # Time, network, backlight
├── assets/         # Fonts and icons
├── device/         # device.yaml, sensors.yaml, lvgl.yaml
├── esphome/        # template.yaml
├── theme/          # Button and UI styling
└── guition-esp32-s3-4848s040.jpg
```

Customize for your setup by editing the YAML files under `device/`, `addon/`, and `theme/`. See the [main README](../README.md) for full quick start and ESPHome setup.
