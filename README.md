tinkerforge-munin
===============

Munin Plugins for tinkerforge sensors

## Jump to Section
* [How to install](#how-to-install)
* [Notes](#notes)
* [License](#license)
* [Donate Me ![](https://www.paypalobjects.com/de_DE/DE/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TZMF3HP322F5U)

## How to install
---
[[Back To Top]](#jump-to-section)

Copy plugins from the 'plugins' folder:

    cp plugins/* /usr/share/munin/plugins

Create symlink for your devices (run as root)
    
    munin-node-configure --suggest --shell

#Create list of threshold keys (run as root)
#
#    /usr/share/munin/plugins/TF_TemperatureIR_ suggest env >> /etc/munin/plugin-conf.d/tinkerforge
#    /usr/share/munin/plugins/TF_Moisture_ suggest env >> /etc/munin/plugin-conf.d/tinkerforge
#
#Afterwards you need to set to proper values for these keys, according to your needs.

## Notes
---

## License
---
[[Back To Top]](#jump-to-section)

Copyright © 2013 Sascha Curth

This software is licensed under [MIT License](http://scurth.mit-license.org/).
