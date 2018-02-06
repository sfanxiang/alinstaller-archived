AL Installer
============
AL Installer is an installer for [Arch Linux](https://www.archlinux.org/). It is
intended for desktop use and provides a dialog-based installation guide to
perform a clean installation without the need of Internet access.

The [GNOME](https://www.gnome.org/) desktop environment and several common
drivers are installed by default. Minimal configuration is done to ensure an
out-of-the-box experience.

## Install

Download the ISO image from [Releases](../../releases), and boot from it.

## Build

Note: AL Installer needs to be built in Arch Linux.

Install the [archiso](https://www.archlinux.org/packages/?name=archiso) package,
and run:

```sh
./build.sh
```

(Warning: `build.sh` may install packages on your host system.)
