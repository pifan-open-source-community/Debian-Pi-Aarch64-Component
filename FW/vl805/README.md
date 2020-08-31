#Update VL805 pcie to usb3 bridge firmware

This is not a necessary step.

This procedure will slightly increase usb3 performance.

```
chmod +x vl805
sudo ./vl805 -w vl805-000138a1.bin
sudo reboot
```
