# 🎨 Inkustrator

A patch for optimizing Inkscape 1.2.1+ for Adobe Illustrator users, including features like:

* UI organization to mimic Adobe Illustrator;
* Fixed Adobe Illustator shortcuts similar to the ones in Illustrator for Windows, following [Adobe’s Documentation](https://helpx.adobe.com/es/illustrator/using/default-keyboard-shortcuts.html);

(It's like [Diolinux's PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) but instead of Photoshop to GIMP it's Illustrator to Inkscape) 

## ⚙ Install

Remove inkscape configuration folder<br>
[Install inkscape](https://inkscape.org/release/)<br>
Start Inkscape and set:<br>
`Edit > Preferences > Interface > Keyboard > Keyboard file > Adobe Illustrator (adobe-illustrato-cs2.xml)`<br>
Close Inkscape<br>
Download last zip Inkustrator release and past content into configuration folder (if it doesn't exist, create it)

## ⚙ Ubuntu/Debian or derivatives

Use this all in one installer instead.

## ⚙ Other Linux or Unix(-like) system

Don't use package version, install last Inkscape:
* [AppImage](https://inkscape.org/release/all/gnulinux/appimage/)
* [Flatpack](https://flathub.org/apps/details/org.inkscape.Inkscape)
* [Snap](https://snapcraft.io/inkscape)

Flatpack/AppImage configuration folder: `$HOME/.config/inkscape`<br>
Snap configuration folder: `$HOME/snap/inkscape/5874/.config/inkscape/`

## macOS

Configuration folder: `"$HOME/Library/Application Support/Inkscape/"`

## Windows

Configuration folder: `%APPDATA%\Inkscape`

## Credits
* [Inkscape](https://inkscape.org/)
* [Diolinux PhotGIMP](https://github.com/Diolinux/PhotoGIMP) project
* [Jesús David Navarro, jEsuSdA 8](https://www.jesusda.com/projects/colorpalettes/index.html)

## References
* [How to make INKSCAPE look like Illustrator 2020](https://youtu.be/fzEjBldtba4)
* [Inkscape for Adobe Illustrator users](https://wiki.inkscape.org/wiki/Inkscape_for_Adobe_Illustrator_users)
* [Adobe default keyboar shortcuts](https://helpx.adobe.com/es/illustrator/using/default-keyboard-shortcuts.html)
