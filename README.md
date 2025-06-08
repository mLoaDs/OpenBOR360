# OpenBOR360
OpenBOR360 v3.0 Build 3688 ported by A600

This is an OpenBOR port for the Xbox360, possible thanks to the hard work of
the OpenBOR and Senile teams, the SDLx libs by lantus and the XBDM plugin
by Natelx.

<p align="center">
  <img width="400" height="175" src="https://github.com/user-attachments/assets/964d11e3-51c9-4730-853b-ccfb71e0febc">
</p>

<p align="center">
    <a href="https://github.com/mLoaDs/OpenBOR360/releases/tag/OpenBORv3.0" class="btn btn-primary">OpenBOR360 v3.0 Download</a>
</p>

KNOWN BUGS
----------
> [!IMPORTANT]
> The BGM player doesn't work so, for now, is disabled.
> Ogg music isn't played (works but doesn't sound right) so also is disabled.
  The only workaround is to convert the .ogg files to .bor: Unpack the pak,
  convert the oggs to wav, then use wav2bor with those wavs, rename the final
  files to .ogg and repack the pak.
  Anyway, only a few paks use ogg music.

> [!NOTE]
> In the download area you will find the OBOR tools for packing and unpacking the .pak files and converters for the .ogg files
>
> Instructions on how to do this can be found here: [How to unpack and package OpenBOR .pak games](https://openborgames.com/how-to-unpack-and-package-openbor-pak-games#more-1375)

CONTROLS
--------

Dpad 			-> Up/Down/Left/Right

A			-> Button1

B 			-> Button2

X 			-> Button5

Y 			-> Button6

Left Trigger 		-> Button3

Right Trigger 		-> Button4

Back			-> Escape

Start			-> Start

Right Analog Thumb	-> Screenshot



All controls can be remapped using the "Control Options" menu.


SCREEN
------
> [!NOTE]
> If you are using the 720p videomode, to get a correct aspect ratio for those
> 4:3 paks, select the menu "Video Options" - "Aspect Ratio" and set it to 4:3.

> [!TIP]
> The xResizer.xex included allows to resize the screen for those with overscan problems.
>
> It generates an xbox.cfg with these default settings:
>
> xpos=0
> ypos=0
> xstretch=0
> ystretch=0
