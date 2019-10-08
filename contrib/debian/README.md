
Debian
====================
This directory contains files used to package bitcoininvestd/bitcoininvest-qt
for Debian-based Linux systems. If you compile bitcoininvestd/bitcoininvest-qt yourself, there are some useful files here.

## bitcoininvest: URI support ##


bitcoininvest-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoininvest-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoininvestqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoininvest128.png` to `/usr/share/pixmaps`

bitcoininvest-qt.protocol (KDE)

