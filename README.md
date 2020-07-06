# i3 Aswath

* To move monitor position

install xrandr
sudo apt-get install x11-xserver-utils

then
xrandr --output VGA-1 --right-of HDMI-1


Customize status bar
https://medium.com/hacker-toolbelt/my-i3status-customization-3e8ad6f0153a


* To find class name to use for assigning certain applications to certain windows, 
run $xprop, and click on the application.

* To control audio install pavucontrol
$sudo apt install pavucontrol

* To add daedalus to the D Menu
sudo ln -s ~/.local/bin/daedalus-mainnet /usr/bin/daedalus-mainnet
