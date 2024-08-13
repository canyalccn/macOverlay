# macOverlay
A simple hammerspoon script to add a constant overlay on top of monitor screen, even above fullscreen windows. For macOS.

Main Purpose

If you want a constant overlay on top of your screen for some reason, you can use this script.

IMPORTANT STUFF

I created this script with the help of ChatGPT and some common sense.

How to use:

1. If you haven't already, install Hammerspoon.
2. Open the config file (init.lua) by right clicking the hammerspoon icon on the menu.
3. Copy this script into init.lua or just swap the file itself with the one here.
4. In the script, change the your/path/to/file to your actual path to file. (for example: User/username/Desktop/file.png
5. Reload the Config on console.
6. Press Ctrl-Cmd-Alt + O (letter) to activate the overlay.

Notes:
 
Shortcut can be changed through the script. You need the overlay_stopped/overlay_activated.png on your desktop if you want the notifications to work.
There is a slight delay for overlay to be applied. Keep in mind that everytime you change a screen mode overlay gets refreshed (to keep it on top)

Known issues:

Notification PNGs don't show up when on fullscreen.

Lots of spagetthi code.



I'm just putting this here so that people in need can grab it or develop it even further. I couldn't find such an app which does this the exact thing.

To be honest I didn't put much effort into this, but it does the job for me. Maybe in future I will look into the script more in detail and consider to turn it to a fully executional app with GUI.
