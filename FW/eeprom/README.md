# Update Raspberrypi 4B EEPROM

You need to update the eeprom with sd card booted OS, not usb booted one.

请使用sd卡启动的系统升级eeprom，usb启动的系统无法正常升级eeprom
```
sudo rpi-eeprom-update -d -f ./pieeprom-xxxxxx.bin
sudo reboot
```
