Dream Machine: rEFInd theme
==============================
rEFInd is a really neat bootmanager, here's a neat dark theme for it.

Editable bg found in /originals.

Screendump
----
![dream-machine-theme](https://raw.githubusercontent.com/Lindstream/dm-refind-theme/master/screenshot.jpg)

Installation
----
```
$root: cp -r ./dm-refind /boot/EFI/refind
$root: vim /boot/EFI/refind.conf
``` 

Change the following options:
```
hideui singleuser,arrows,hints,badges
icons_dir dm-refind/icons
banner dm-refind/background.png
selection_big dm-refind/selection_big.png
selection_small dm-refind/selection_small.png

```

Attribution
----

Font: Coding Font Tobi

The OS icons are from [Lightness for burg][icons] by [SWOriginal][icon-author].

[icons]: http://sworiginal.deviantart.com/art/Lightness-for-burg-181461810
[icon-author]: http://sworiginal.deviantart.com/