# photon-native-css

A userChrome.css to apply on top of Photon (Firefox 57+) that uses more native OS elements.

Put userChrome.css in a folder called "chrome" in your profile directory. Then restart Firefox and enable the light theme.

If you're using macOS, there's a rule commented out in the file that you'll probably want to enable.

Tested on:

* Windows 10 (looks good)
* Windows 7, default theme (looks good)
* Windows 7, classic theme (looks good; the toolbar buttons are just CSS)
* macOS High Sierra (the buttons could use some work)
* Unix+GTK3 (looks good on light and dark themes, might need to customize searchbar height)
