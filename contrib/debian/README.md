
Debian
====================
This directory contains files used to package threadcoind/threadcoin-qt
for Debian-based Linux systems. If you compile threadcoind/threadcoin-qt yourself, there are some useful files here.

## threadcoin: URI support ##


threadcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install threadcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your threadcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/threadcoin128.png` to `/usr/share/pixmaps`

threadcoin-qt.protocol (KDE)

