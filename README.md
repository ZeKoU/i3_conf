# My i3 Configuration 
### Read about i3 window manager here: http://i3wm.org/

## Requirements
### general
* i3 - window manager
* i3status - status bar
* feh - setting bg, also nice image viewer
* urxvt - terminal emulator
* unclutter - autohide mouse cursor
* udiskie - device automounting
* dunst - notifications
* pulseaudio - audio managment
* autocutsel - clipboard synchroniation
* dmenu - Super-P launcher
* pavucontrol - pulseaudio mixer
* alsamixer
### from xorg
* setxkbmap - setting keyboard layout
* xmodmap - custom key changes


##Installation
It's as simple as that:

```bash
cd
git clone https://github.com/ZeKoU/i3_conf .i3
ln -s .i3/xinitrc .xinitrc
ln -s .i3/gtkrc-2.0 .gtkrc-2.0
```

##Bindings
Super --> Windows key (unused on Linux)

* Super-c - kill focused window
* Super-Enter - open terminal
* Super-v - split in horizontal orientation
* Super-g - split in vertical orientation
* Super-f - enter fullscreen mode
* 
* Super-s - resize mode
* Super-Left - shrink width in resize mode
* Super-Right - grow width in resize mode
* Super-Down - shrink height in resize mode
* Super-Up - grow height in resize mode

* Super-n - toogle tabbed layout
* Super-m - toggle split layout
* Super-Space - change focus between tiling / floating windows

* Super-z - reload configuration
* Super-Shift-x - restart
* Super-Shift-z - exit

Check config for more...