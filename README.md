# 🎨 Inkustrator

A patch for optimizing Inkscape 1.2.1+ for Adobe Illustrator users, including features like:

* UI organization to mimic Adobe Illustrator;
* Fixed Adobe Illustator shortcuts similar to the ones in Illustrator for Windows, following [Adobe’s Documentation](https://helpx.adobe.com/es/illustrator/using/default-keyboard-shortcuts.html);

(It's like [Diolinux's PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) but instead of Photoshop to GIMP it's Illustrator to Inkscape) 

## ⚙ Ubuntu/Debian or derivatives

Use this installer

## ⚙ Other Linux or Unix(-like) system

Remove `$HOME/.config/inkscape`
Don't use package version, install last Inkscape instead with:
* AppImage
* Flatpack
* Snap

Open Inkscape and set:<br>
`Edit > Preferences > Interface > Keyboard > Keyboard file > Adobe Illustrator (adobe-illustrato-cs2.xml)`

Download last release zip and extract it.

If Flatpack or AppImage paste config folder content into this folder (if not exist, create it)
`$HOME/.config/inkscape`
IF Snap do the same but use this folder instead:
`$HOME/snap/inkscape/5874/.config/inkscape/`

### macOS

Configuration folder: `"$HOME/Library/Application Support/Inkscape/"`

### Windows

Configuration folder: `%APPDATA%\Inkscape`

## Credits

* This project would not be possible without the amazing GIMP team.
* The Photo in the new Splash is from [Isabella Mariana](https://www.pexels.com/pt-br/@isabella-mariana-1022505)
* A BIG thanks to all Diolinux’s supporters on [Twitch](https://twitch.tv/Diolinux) and [YouTube](https://youtube.com/Diolinux).

## Patch Notes
-  [Veja as Notas de Lançamento em Português](https://diolinux.com.br/2020/06/photogimp-2020.html)
