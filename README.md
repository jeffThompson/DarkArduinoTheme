![screenshot](https://raw.githubusercontent.com/jeffThompson/DarkArduinoTheme/master/screenshot.png)

# Dark Arduino Theme

### NOTE  
**Sadly, I'm no longer maintaining this theme. The Arduino IDE has changed a lot but I'm not doing much work with the platform and it's just too much to keep this up-to-date.** If you'd like to fork the repo and fix it, that would be great! I'll happily add a link to your version here so others can benefit.

Still works for Arduino version 1.8.5+, not tested with newer/older versions.

\- \- \-

### INSTALLATION  

* Mac users should look in `/Applications/Arduino.app/Contents/Java/lib` and replace the `theme` folder inside (making a copy of the original in case want to revert back).  
* Windows is located in `C:\Program Files (x86)\Arduino\lib`.  
* Linux will be in `/usr/share/arduino/lib/` – note you may need to install the Arduino IDE from the Arduino site, not a place like Ubuntu Software  

### CREATING YOUR OWN MODS
The newest version of the Arduino IDE makes creating custom themes trickier: you now need to edit the `theme.txt` file, an XML file inside the `syntax` folder, and the button files. Unfortunately, not all items in the `theme.txt` file actually work, so if you can't get an item to change, try another one of the files.

\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).
