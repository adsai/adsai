
Debian
====================
This directory contains files used to package adsaid/adsai-qt
for Debian-based Linux systems. If you compile adsaid/adsai-qt yourself, there are some useful files here.

## adsai: URI support ##


adsai-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install adsai-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your adsaiqt binary to `/usr/bin`
and the `../../share/pixmaps/adsai128.png` to `/usr/share/pixmaps`

adsai-qt.protocol (KDE)

