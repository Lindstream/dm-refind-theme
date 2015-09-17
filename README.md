Dream Machine: rEFInd theme
==============================
This is a neat dark theme for rEFInd[refurl]

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
$root: cp -r ./dm-refind-theme /boot/EFI/refind-theme
$root: vim /boot/EFI/refind.conf
``` 

Change the following options:
```
hideui singleuser,arrows,hints,badges,label
icons_dir dm-refind-theme/icons
banner dm-refind-theme/background.png
selection_big dm-refind-theme/selection_big.png
selection_small dm-refind-theme/selection_small.png

```

Attributions
----

**Font:** Coding Font Tobi

**Icons:** [Lightness for burg][icons] by [SWOriginal][icon-author].

[icons]: http://sworiginal.deviantart.com/art/Lightness-for-burg-181461810
[icon-author]: http://sworiginal.deviantart.com/
[refurl]: http://www.rodsbooks.com/refind/