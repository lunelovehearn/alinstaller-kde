AL Installer
============
AL Installer is an installer for [Arch Linux](https://www.archlinux.org/). It is
intended for desktop use and provides a step-by-step installation guide to
perform a clean installation without the need of Internet access.

The [GNOME](https://www.gnome.org/) desktop environment and several common
drivers are installed by default. Minimal configuration is done to ensure an
out-of-the-box experience.

## Install

Download the ISO image from [Releases](../../releases), and boot from it.

## Build

Note: AL Installer needs to be built in Arch Linux.

Install [archiso](https://www.archlinux.org/packages/?name=archiso), and run the
following as root:

```sh
./build.sh
```

Output will be written to `build/out/alinstaller.iso`.

## Translate

You can edit the translation by editing the `.po` files inside `locale/`. New
languages need to be added to `src/lang.txt` and `misc/*.desktop`. Run
`make-locale.sh` to regenerate the locale files.

## Distros based on Arch Linux

Anarchy Linux (originally _Arch Linux Anywhere_): https://anarchy-linux.org/  
Antergos: https://antergos.com/  
Manjaro Linux: https://manjaro.org/
