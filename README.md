# MP Select Mini Cura 2 Plugin
This allows WIFI printing from within Cura 2.x with the popular inexpensive [MonoPrice MP Select Mini](http://www.monoprice.com/product?p_id=15365) 3D printer.

### Warning ###
Use this plugin at your own risk. I am not responsible for any damage caused by the use of this plugin.

### Installing ###
1. Copy the 'MPSelectMiniOutputDevice' folder to the plugins folder within the installation directory of Cura 2.x
2. Configure setting by either:
  1. Opening 'LocalFileOutputDevicePlugin.py', setting, and uncomminting the variables near the top of the code
  2. Opening cura.cfg and adding the following lines:
```
[MPSelectMini]
ip = 192.168.1.123
start_print = True
```
