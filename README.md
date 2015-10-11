# Alternate OSX Icons
> Some alternative icons I have made for some OS X icons that you can use as replacements for the defaults.

## Installation

### If your OS X is Mavericks or older
1. Right-click the application in your Applications folder and select ‘Get Info’
2. In another window, select the .icns file and then copy it by right-clicking or by pressing ⌘C
3. In the Info window, select the small icon at the top left by clicking on it and then press ⌘V, pasting the new icon in. Remove the old app from your dock and re-add it in.

### If your version of OS X is El Capitan or newer
El Capitan has made it more difficult to replace icons.

1. Run the following in Terminal to disable Rootless:
`sudo nvram boot-args="rootless=0”`
2. Reboot your computer.
3. Follow steps 1-3 in the previous section
4. Optionally, you can re-enable Rootless by opening Terminal and running: `sudo nvram boot-args="rootless=1”`

### Credits
- The uppercase ‘G’ featured in the Glyphs icon is taken from Fuego Serif, an unreleased typeface by [Justin Sloane](http://justinsloane.com/).

## License
The icons are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).