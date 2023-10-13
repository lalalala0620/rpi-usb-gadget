# rpi-usb-gadget
Script for setting up a Raspberry PI 4 as a USB gadget, and letting the PC connect to RPI through USB-C.
```
git clone git@github.com:lalalala0620/rpi-usb-gadget.git
```
```
bash rpi4-usb.sh
```
```
sudo reboot
```
Suppose you want to change the IP address. First:
```
bash remove.sh
```
Change "rpi4-usb.sh" lines 11, 12 and 102.
Then:
```
bash rpi4-usb.sh
```
```
sudo reboot
```
## References:
- https://github.com/kmpm/rpi-usb-gadget
