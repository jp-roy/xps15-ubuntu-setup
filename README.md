# xps15-ubuntu-setup

## Improving Battery Life
```
sudo apt install powertop
sudo gedit /etc/rc.local
```

paste in the following (before the exit 0 line)
```
powertop --auto-tunew
```

## OLED Brightness control

https://github.com/udifuchs/icc-brightness
https://unix.stackexchange.com/questions/150816/how-can-i-lazily-read-output-from-xrandr
https://github.com/TillmannBerg/Ubuntu-Dell-XPS-15-2019/blob/master/dell-brightness.sh

## Ubuntu random freezes

For the moment, trying this on google chrome :
https://askubuntu.com/questions/765974/chrome-freeze-very-frequently-with-ubuntu-16-04

Deactivate Hardware acceleration
- Type "chrome://settings" in the URL bar
- click "Advanced"
- Untick "use hardware acceleration when available"

Disable GPU Rasterization
- Go to "chrome://flags"
- Disable "GPU Rasterization"
