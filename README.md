# Belliot
EspHome based software for Belliot hardware. I use this to control my Siedle HTA 511-01 from Home Assistant.

Hardware for this lives here: https://github.com/vondraussen/belliot

Feature:
+ Silent Bell (via remote or push button)
+ actuate the door opener
+ automatic door opener on ring

## Build
```bash
python -m esphome run belliot.yaml
```

## Install Esphome
```bash
pip install esphome
```
