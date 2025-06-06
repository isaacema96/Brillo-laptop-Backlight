Install package:
```sh
sudo pacman -S xbacklight
```
Enter the following path and paste the 99-backlight_clamp.rules file:
to set the brightness from start to zero
```sh
cd /etc/udev/rules.d/
```

Reboot and then check if the brightness has changed.
```sh
 cat   /sys/class/backlight/amdgpu_bl1/brightness
```


