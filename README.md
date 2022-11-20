# 🎨 Inkustrator

A patch for optimizing Inkscaoe 1.2.1+ for Adobe Illustrator users, including features like:

* UI organization to mimic Adobe Illustrator;
* Fixed Adobe Illustator shortcuts similar to the ones in Illustrator for Windows, following Adobe’s Documentation;

(Like [Diolinux's PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) but instead of Photoshop to GIMP it's Illustrator to Inkscape) 

## ⚙ Linux

Remove `$HOME/.config/inkscape`
Install last Inkscape, options:
- 



This package is all about flatpak, but it also contains "just files" that you can use on any version of GIMP (.deb, .rpm, Snap, AppImage, Windows, macOS). Just check the location of the GIMP configuration files.

**Start and quit GIMP after you installed before you continue!**

### Prepare the Flatpak enviroment

*If you have previously had GIMP installed via .deb, .rpm, etc., please ensure you delete the directory `$HOME/.config/GIMP`, as this may cause conflicts with the Flatpak config files.*
* First of all, you need to have the latest GIMP installed on your system [using Flatpak](https://flatpak.org/setup/)
* Install GIMP Flatpak through your AppCenter/Package Manager or terminal:
```flatpak install flathub org.gimp.GIMP```

## ⚙ How to Install (others)

Since it’s just files, the only thing you need to do is to copy all the files that reside on a particular folder from this package `/.var/app/org.gimp.GIMP/config/GIMP/2.10` to your GIMP’s configuration folder on each particular system, overriding the existent ones.

**Start and quit GIMP after you installed before you continue!**

The new icon needs to be set manually.

### Ubuntu Snap

Configuration folder: `$HOME/snap/gimp/47/.config/GIMP/2.10/`

### Other Linux or Unix(-like) systems (.deb, .rpm, etc.)

Configuration folder: `$HOME/.config/GIMP/2.10/`

### macOS

Configuration folder: `"$HOME/Library/Application Support/GIMP/2.10/"`

* [Video Tutorial by Davies Media Design on macOS](https://youtu.be/5nXhtaGQs9U)

This one-liner will do the job:
```console
curl -L https://github.com/Diolinux/PhotoGIMP/releases/download/1.0/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip -o ~/Downloads/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip && unzip ~/Downloads/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip -d ~/Downloads && cp -R ~/Downloads/PhotoGIMP\ by\ Diolinux\ v2020\ for\ Flatpak/.var/app/org.gimp.GIMP/config/GIMP/2.10/ ~/Library/Application\ Support/GIMP/2.10 && rm ~/Downloads/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip
```
(downloads release 1.0 into `Downloads` folder, unzips and copies files, then removes downloaded .zip file)

*Notice*: GIMP on macOS is a bit late on its release. This way, this patch still works, specially on the shortcuts matter, but somethings, such the toolbox organization, will not work properly. Until the macOS version reaches the version 2.10.20, expect this behavior.

### Mac OS Easy Installer (maded by: [@MatthijsKamstra](https://github.com/MatthijsKamstra))

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/MatthijsKamstra/Mac-setup/master/install/photogimp_osx.sh)"
```

### Windows

Configuration folder: `%APPDATA%\GIMP\2.10`

* [Video Tutorial by Davies Media Design on Windows](https://youtu.be/57DNUsf4A-0)

Or install via [Chocolatey](https://chocolatey.org/):
```powershell
choco install photogimp
```
Maintained by: [André Augusto](https://github.com/AndreAugustoAAQ)

## Credits

* This project would not be possible without the amazing GIMP team.
* The Photo in the new Splash is from [Isabella Mariana](https://www.pexels.com/pt-br/@isabella-mariana-1022505)
* A BIG thanks to all Diolinux’s supporters on [Twitch](https://twitch.tv/Diolinux) and [YouTube](https://youtube.com/Diolinux).

## Patch Notes
-  [Veja as Notas de Lançamento em Português](https://diolinux.com.br/2020/06/photogimp-2020.html)
