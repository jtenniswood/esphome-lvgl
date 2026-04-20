# Guition ESP32-P4 JC4880P443 (4.3")

4.3-inch touch LCD panel with ESP32-P4 and ESP32-C6 WiFi coprocessor, running ESPHome and LVGL for home automation and sensor displays.

## Configuration

- **Template**: [esphome.yaml](esphome.yaml) - use the **contents of this file as your ESPHome config** in the dashboard or CLI (create or edit your device config so it matches this file).

## Folder Structure

```
guition-esp32-p4-jc4880p443/
├── addon/          # Time, network, backlight
├── assets/         # Fonts and icons
├── device/         # device.yaml, sensors.yaml, lvgl.yaml
├── spares/         # Optional hardware features
├── theme/          # Button and UI styling
├── esphome.yaml    # ESPHome config template
```

Customize for your setup by editing the YAML files under `device/`, `addon/`, and `theme/`. See the [main README](../README.md) for full quick start and ESPHome setup.
