# Waveshare ESP32-P4-WIFI6-Touch-LCD-4B

4-inch 720x720 touch LCD panel with ESP32-P4, ESP32-C6 Wi-Fi coprocessor, MIPI-DSI display, and GT911 capacitive touch.

## Configuration

- **Template**: [esphome.yaml](esphome.yaml) — use the **contents of this file as your ESPHome config** in the dashboard or CLI.
- **Display model**: `WAVESHARE-P4-86-PANEL`
- **Touch**: GT911 over I2C on GPIO7/GPIO8
- **Backlight**: GPIO26, inverted PWM

## Where to Buy

- **Panel**: [Waveshare](https://www.waveshare.com/esp32-p4-wifi6-touch-lcd-4b.htm)

## Folder Structure

```
waveshare-esp32-p4-wifi6-touch-lcd-4b/
├── addon/          # Time, network, backlight
├── assets/         # Fonts and icons
├── device/         # device.yaml, sensors.yaml, lvgl.yaml
├── theme/          # Button and UI styling
├── esphome.yaml    # ESPHome config template
```

Customize for your setup by editing the YAML files under `device/`, `addon/`, and `theme/`. See the [main README](../README.md) for the full quick start and ESPHome setup.
