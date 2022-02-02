-----System tools  / setup-----
Nvidia driver
Logiops
Superpaper
Quicktile
PA_Cycle_Sink / pavucontrol
Autokey?
Nautilus
Laptops: tlp(tlpui)/laptop-mode-tools
Stacer
Timeshift (Zotero, Notes, Calibre, Files)
Gnome-disk-utility / gparted
Gnome Tweaks
pyenv, pip, python3-pip-autoremove (pip3-autoremove)
tldr
/usr/share/applications/org.gnome.FileRoller.desktop -> Exec=file-roller -h
Nvidia settings Force Composition Pipeline

-----Apps-----
Zotero (Mendely?)
Calibre
VLC
Steam
Chrome
LibreOffice: Writer/Calc (Impress/Draw?) / OnlyOffice
Anki
Simplenote
Joplin + Typora
Discord
VSCode, CLion (Edu)
Calculator (Idle)
Shellcheck
Youtube-dl / yt-dlp / ytmdl
Mediainfo
Music
Ardour
PDF Arranger
CodeEditor: Elementary Code / Notepadqq
App Outlet
KDEnlive

-----To Do-----
Append copy/paste
Device copy/paste
Backups system (rsync?)
Gimp

-----Keyboard Shortcuts-----
3 :	Go to left workspace
4 :	Go to right workspace
1 :	Move window to left workspace
2 :	Move window to right workspace
7 :	Maximise
7 :	Minimise

UHD+Vert (UWQHD?)
5 :	Switch Screen
5 :	Tile window left (cycle col width)
6 :	Tile window right (cycle col width)
6 :	Tile window top (cycle col width)
6 :	Tile window bottom (cycle col width)
6 :	Tile window top-left (cycle col width)
6 :	Tile window top-right (cycle col width)
6 :	Tile window bottom-left (cycle col width)
6 :	Tile window bottom-right (cycle col width)
6 :	Tile window center (cycle col width)

Apps:
:	Libre Office
:	Anki
:	Joplin
:	Simplenote
:	Discord
:	Zotero
:	TextEditor (Elementary Code)
:	Chrome
:	Files
:	Terminal
:	Calculator
:	Screenshot
:	Cycle Audio Output
:	Music
:	Switchboard (Settings)
:	Calibre

System:
Opt+Tab:	Expose
Alt+Tab:	Cycle Apps
Ctrl+Up:	Jump up ten lines
Ctrl+Down:	Jump down ten lines
Terminal: stty (delete/highlight word)

Text:
Ctrl+Backspace:		Delete word back
Ctrl+Del:					Delete word forth
Cmd+Backspace:	Delete line back
Cmd+Del:				Delete line forth
Move line up:			Cmd+Up
Move line down:		Cmd+Down
Go 10 lines up:		Ctrl+Up
Go 10 lines down:	Ctrl+Down
Cut Line
Copy Line
Duplicate Line
Go word back
Go word forth

-----Next install-----
home partition
Pip installs to user dir
System Tray
	https://www.youtube.com/watch?v=0yOoOyxCQ24
	https://gist.github.com/inercia/3f11aa96dd80bb1c2056745c8a9b0f7d


-----Useful commands / reference-----

dpkg -i *.deb, apt install ./*.deb
apt [update, upgrade, list [--installed], search, show, [--fix-broken | -f] install, remove, autoremove]
apt-cache [rdepends]
tar -xvf file.tar
df -h
chmod -x file.exe
unzip -B (renames)
nvidia-smi
/etc/X11/default-display-manager
$GDMSESSION
rm /etc/X11/xorg.conf -> systemctl restart lightdm / sudo restart lightdm
startx, xinit
killall gsd-media-keys
lsmod
xev, evtest, showkey
sudo fdisk -l
sudo mkfs.exfat -n LABEL /dev/sdXn
rfkill list, rfkill unblock bluetooth 
xmodmap
Input Event Codes: https://github.com/torvalds/linux/blob/master/include/uapi/linux/input-event-codes.h
