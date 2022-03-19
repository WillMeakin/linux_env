-----System tools  / setup-----
Nvidia driver
Logiops
Quicktile
Superpaper / Hydrapaper
PA_Cycle_Sink / pavucontrol
Autokey -----?-----
Nautilus
Laptops: tlp(tlpui)/laptop-mode-tools
pyenv, pip, python3-pip-autoremove (pip3-autoremove) -----?-----
tldr -----?-----
/usr/share/applications/org.gnome.FileRoller.desktop -> Exec=file-roller -h
Nvidia settings Force Composition Pipeline
wingpanel-indicator-ayatana
PavuControl-qt, Pasystray
Pantheon tweaks (gnome tweaks)
Dconf-tools
gsettings set org.gnome.desktop.privacy remember-recent-files false
dircolors --print-database, dircolors -p > ~/.dircolors, eval "$(dircolors ~/.dircolors)";

-----Apps-----
Chrome
Steam
Zotero (Mendely?)
VLC
LibreOffice: Writer/Calc (Impress/Draw?) / OnlyOffice
Simplenote
Anki
Discord
Calculator (Idle)
CodeEditor: Elementary Code / Notepadqq
PDF Arranger
Gparted / gnome-disk-utility
Mediainfo
Youtube-dl / yt-dlp / ytmdl
Puddletag
Calibre
Stacer
Transmission
VSCode, CLion (Edu)
Shellcheck
Music
Ardour
App Outlet
KDEnlive

-----To Do-----
Logid shortcuts
Append copy/paste
Device copy/paste
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
Opt+`:	Expose
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

-----Useful commands / reference-----
dpkg -i *.deb, apt install ./*.deb
apt [update, upgrade, list [--installed], search, show, [--fix-broken | -f] install, remove, autoremove]
apt-cache [rdepends], policy
tar -xvf file.tar.gz
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
find / -name '*.desktop'
sudo fdisk -l
sudo mkfs.exfat -n LABEL /dev/sdXn
rfkill list, rfkill unblock all 
xmodmap
Input Event Codes: https://github.com/torvalds/linux/blob/master/include/uapi/linux/input-event-codes.h
uname -r, linux-headers-version-generic

