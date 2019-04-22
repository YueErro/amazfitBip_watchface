<img src="/imgs/watches.png" align="right" width="1000"></a>
<img width=25/> **Onyx Black <img width=132/> White Cloud <img width=120/> Kokoda Green <img width=114/> Cinnabar Red**

## Table of Contents
- [Requirements](#requirements)
- [Try the example](#try-the-example)
- [Edit the example](#edit-the-example)
- [Useful information](#useful-information)
- [References](#references)

## Requirements
- Amazfit Bip watch
- Mobile phone compatible with:
  - [Mi Fit](https://play.google.com/store/apps/details?id=com.xiaomi.hm.health) app with an account
  - [Amazfit Bip & Cor WatchFaces](https://play.google.com/store/apps/details?id=paolo4c.amazfit.watchfaces) app


```bash
git clone https://github.com/YueErro/amazfitBip_watchface.git
# or download the zip project and unzip it.
```

## Try the example
<img src="/imgs/watch.png" align="left" width="70"></a>

1. You need to have `watchface.png` and `watchface_loader.bin` ([files](https://github.com/YueErro/amazfitBip_watchface/tree/master/example/white_background)) in your mobile phone.
2. Once you have them, open _Amazfit Bip & Cor WatchFaces_ app and click on _Carga .bin (BIP)(Local)_ by clicking first in the three dots in the top right side, and choose those files (.png and .bin from the step 1).
3. Open _Mi Fit_ app and go to _Perfil>Amazfit Bip>Ajustes de apariencia del reloj>Esferas de reloj locales_. If everything is correct you will see the watchface listed there.

## Edit the example
1. Unzip `AmazfitBipTools-1.0.3.1.7z`.
2. Open `watchface_loader.bin` with `WatchFace.exe` (the cmd will open and close automatically) to get `watchface_loader` folder with the corresponding images and json file (you can omit the log file).
3. Edit/Add/Remove the images at your pleasure (screen size of the BIP is 176x176) and edit the json file accordingly and also at your pleasure (read more about [json properties](/JSON.md)). You can make use of an useful GUI at https://v1ack.github.io/watchfaceEditor/ to preview the watchface or even edit the json file. Useful tools for this purpose:
   - [pixlr](https://pixlr.com/editor/) online to edit the images.
   - [image generator](https://v1ack.github.io/watchfaceEditor/imagecreator.html) to create new images

   *The name of the images has to be a number, 0001.png for instance*

4. Once you are done, open the json file with `WatchFace.exe` to do the opposite in order to generate the bin file (the cmd will open and close automatically). You only need the bin file and the static image (you can also generate the png with the desired numbers from the GUI).
5. Transfer these two (.bin and .png) files to the mobile phone and follow the steps in [_Try the example_](https://github.com/YueErro/amazfitBip_watchface#try-the-example) If everything is correct you will see your new watchface listed there.

## Useful information
The color palette is limited, so far being the following one:
- ![#000000](https://placehold.it/15/000000/000000?text=+) Black
- ![#0000FF](https://placehold.it/15/0000FF/0000FF?text=+) Cyan
- ![#00FF00](https://placehold.it/15/00FF00/00FF00?text=+) Green
- ![#FF0000](https://placehold.it/15/FF0000/FF0000?text=+) Red
- ![#00FFFF](https://placehold.it/15/00FFFF/00FFFF?text=+) Blue
- ![#FF00FF](https://placehold.it/15/FF00FF/FF00FF?text=+) Purple
- ![#FFFF00](https://placehold.it/15/FFFF00/FFFF00?text=+) Yellow
- ![#FFFFFF](https://placehold.it/15/FFFFFF/FFFFFF?text=+) White

## References
- [AmazfitBipWF](http://www.amazfitbipwf.com/index.php/manuales/)
- [xdadevelopers](https://forum.xda-developers.com/smartwatch/amazfit/bip-custom-watchface-music-controls-t3746967)

<img width=800/> [amazfit.com](http://en.amazfit.com/bip.html)
