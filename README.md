﻿# MP Select Mini Cura 2 Plugin
This allows WIFI printing from within Cura 2.x with the popular and inexpensive [MonoPrice MP Select Mini](http://www.monoprice.com/product?p_id=15365) 3D printer.

### Warning ###
Use this plugin at your own risk. I am not responsible for any damage caused by the use of this plugin.

I am currently using Cura 2.3.1 and MP Select Mini firmware V27.42.

### Installing ###
1. Copy the 'MPSelectMiniOutputDevice' folder to the plugins folder within the installation directory of Cura 2.x
2. Configure settings by either:
  1. (Option 1) Opening 'LocalFileOutputDevicePlugin.py', setting and uncomment the variables near the top of the code
  2. (Option 2) Opening cura.cfg, adding the following lines and updating the variables:
```
[MPSelectMini]
ip = 192.168.1.123
start_print = True
```

### Possible improvements ###
- UI popup for IP/start print
- Progress bar for upload
- Check to make sure selected printer type is 'MP Select Mini' (for users with multiple printers)
