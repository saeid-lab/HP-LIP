# HP-LIP
hplip for ubuntu

1) sudo apt install hplip (Linux driver for most HP's printers and scanners).

2) sudo apt install hplip-gui (required by hp-plugin).

3) hp-plugin (as normal user).

This plugin is a proprietary "part" of the driver which HP doesn't open-source. The device won't work without it. You will be prompted to accept the terms and install the required plugin for the exact version of the driver you have installed.

4) hp-doctor (to ensure every thing is installed properly, especially the plugin).

5) hp-setup to add the connected device, or use the HP's software (with graphical interface), already installed at this point.

6) Go to Ubuntu System Settings and add a new printer/scanner with HPLIP.


worked with ubuntu 18.04
https://askubuntu.com/questions/1056077/how-to-install-latest-hplip-on-my-ubuntu-to-support-my-hp-printer-and-or-scanner

Useful Links:
https://developers.hp.com/hp-linux-imaging-and-printing/gethplip
https://developers.hp.com/hp-linux-imaging-and-printing/plugins
