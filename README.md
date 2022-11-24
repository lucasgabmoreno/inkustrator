# 🎨 Inkustrator

A patch for optimizing Inkscape 1.2.1+ for Adobe Illustrator users, including features like:

* UI organization to mimic Adobe Illustrator;
* Fixed Adobe Illustator shortcuts similar to the ones in Illustrator for Windows, following [Adobe’s Documentation](https://helpx.adobe.com/es/illustrator/using/default-keyboard-shortcuts.html);
* [Pantano color palettes](https://www.jesusda.com/projects/colorpalettes/index.html)

(Same as [Diolinux's PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) but instead of Photoshop to GIMP it's Illustrator to Inkscape) 

**📷 Screenshot**

<img src="screenshot.png">

## ⚙ Install

1. If you have Inkscape installed, uninstalled it and remove [configuration folder](https://github.com/lucasgabmoreno/inkustrator/edit/main/README.md#-configuration-folders)<br>
2. [Install inkscape](https://inkscape.org/release/)<br>
3. Start Inkscape and set:<br>
`Edit ⟶ Preferences ⟶ Interface ⟶ Keyboard ⟶ Keyboard file ⟶ Adobe Illustrator (adobe-illustrato-cs2.xml)`<br>
4. Close Inkscape<br>
5. Download [last zip Inkustrator release](https://github.com/lucasgabmoreno/inkustrator/releases/latest) and past content into [configuration folder](https://github.com/lucasgabmoreno/inkustrator/edit/main/README.md#-configuration-folders).

## ⚙ Configuration folders

| OS | Configuration folder |
| :--- | :--- |
| Linux Flatpack, PPA and AppImage | *$HOME/.config/inkscape* |
| Ubuntu Snap | *$HOME/snap/inkscape/5874/.config/inkscape/* |
| Windows | *%APPDATA%\Inkscape* |
| MacOS | *$HOME/Library/Application Support/Inkscape/* |

## Credits
* [Inkscape](https://inkscape.org/)
* [Diolinux PhotGIMP](https://github.com/Diolinux/PhotoGIMP) project
* [Jesús David Navarro, jEsuSdA 8](https://www.jesusda.com/projects/colorpalettes/index.html)

## References
* [How to make INKSCAPE look like Illustrator 2020](https://youtu.be/fzEjBldtba4)
* [Inkscape for Adobe Illustrator users](https://wiki.inkscape.org/wiki/Inkscape_for_Adobe_Illustrator_users)
* [Adobe default keyboar shortcuts](https://helpx.adobe.com/es/illustrator/using/default-keyboard-shortcuts.html)
