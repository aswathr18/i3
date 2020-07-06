# i3 Aswath

* To move monitor position

install xrandr
sudo apt-get install x11-xserver-utils

then
xrandr --output VGA-1 --right-of HDMI-1


Customize status bar
https://medium.com/hacker-toolbelt/my-i3status-customization-3e8ad6f0153a

status bar config can be found in `~/.config/i3status/config`


* To find class name to use for assigning certain applications to certain windows, 
run $xprop, and click on the application.
Then select the `second part of WM_CLASS(STRING)` - 
```
Ex 
1. WM_CLASS(STRING) = "daedalus mainnet", "Daedalus Mainnet"
instance is "daedalus mainnet"
class is "Daedalus Mainnet"

2. WM_CLASS(STRING) = "google-chrome", "Google-chrome"
instance is "google-chrome"
class is "Google-chrome".
```

* To control audio install pavucontrol
$sudo apt install pavucontrol

* To add daedalus to the D Menu

```$sudo ln -s ~/.local/bin/daedalus-mainnet /usr/bin/daedalus-mainnet```

* To execute daedalus wallet on startup 
exec_always --no-startup-id ~/.local/bin/daedalus-mainnet
