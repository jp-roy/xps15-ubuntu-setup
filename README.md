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
