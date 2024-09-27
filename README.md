# nowdabire-keyboard
--- Unity, GNOME 3+, Cinnamon, KDE

To add Nowdabira keyboard layouts to the system, extract the tar.gz file, open a Terminal (with Ctrl+Alt+T) and run:
	cd /path/to/the/extracted/folder/
	sudo cp nd /usr/share/X11/xkb/symbols
	sudo cp evdev.xml /usr/share/X11/xkb/rules

On Ubuntu, to add Nd icons to the indicators, just copy icons content to ~/.icons/, or better yet to run:
	sudo cp -r icons/* /usr/share/icons/
	sudo rm /usr/share/icons/ubuntu-mono-{dark,light}/icon-theme.cache

If you had installed older versions of Nowdabire keyboard before, you may need to update the keyboard
layout configuration to make changes take effect:
	sudo dpkg-reconfigure xkb-data

--- GNOME 2, MATE

Extract the tar.gz file, open a Terminal (with Ctrl+Alt+T) and run:
	cd /path/to/the/extracted/folder/
	sudo cp {nd,MATE/ir} /usr/share/X11/xkb/symbols
	sudo cp MATE/evdev.xml /usr/share/X11/xkb/rules


Then, you can select any layout; Nowdabire, Nowdabire Optimal, Nowdabire (Colemak), Nowdabire (US), or/and Persian Superstandard:
