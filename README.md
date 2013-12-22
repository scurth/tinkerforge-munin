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

You may want to create warning/critical threshold for your measurements as well.

## Notes
---

## License
---
[[Back To Top]](#jump-to-section)

Copyright © 2013 Sascha Curth

This software is licensed under [MIT License](http://scurth.mit-license.org/).
