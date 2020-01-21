# esp_wd
[ESPEasy](https://www.letscontrolit.com/wiki/index.php/ESPEasy) - status sensor
## Example configuration.yaml
```yaml
binary_sensor:
  - platform: esp_wd
    name: bedroom
    host:  http://<host_or_ip>/sysinfo
    scan_interval: 600
```
If 'Admin Password' is set - use standard HTTP auth form.
```yaml
    host:  http://admin:<pass>@<host_or_ip>:<port>/sysinfo
```
![Screenshot](https://github.com/kodi1/esp_wd/blob/master/images/esp_wd.png?raw=true)

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)
