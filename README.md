Dream Machine: rEFInd theme
==============================
This is a neat dark theme for [rEFInd][refurl]

Nametagged background located in /originals, make your changes and save as background.png

Screendump
----
**Clean**
![dream-machine-theme](https://raw.githubusercontent.com/Lindstream/dm-refind-theme/master/screenshot.jpg)


**Nametag**
![dream-machine-theme](https://raw.githubusercontent.com/Lindstream/dm-refind-theme/master/screenshot_nametag.jpg)


Installation
----
```
# Create the theme folder in /boot/EFI/refind if it doesn't exist. Be sure that the folder refind is in /boot/EFI; if not, find it and replace the path with yours in the following commands.
$root: mkdir /boot/EFI/refind/themes
#Copy the folder
$root: cp -r ./dm-refind-theme /boot/EFI/refind/themes/
``` 

Add this line at the end of /boot/EFI/refind/refind.conf:
```
include themes/dm-refind-theme/theme.conf
```
and comment other `include <theme.conf>` lines with a `#`.

Attributions
----

**Font:** Coding Font Tobi

**Icons:** [Lightness for burg][icons] by [SWOriginal][icon-author].

[icons]: http://sworiginal.deviantart.com/art/Lightness-for-burg-181461810
[icon-author]: http://sworiginal.deviantart.com/
[refurl]: http://www.rodsbooks.com/refind/
