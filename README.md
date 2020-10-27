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
