> [!IMPORTANT]
> All of this is soon going to be worthless, since X11 is being deprecated cuz it's straight up shit

# i3-plasma
Allows you to use the i3 window manager with KDE Plasma desktop environment

## Prerequisites
KDE Plasma, a display manager (SDDM works), X11 (__Wayland will not work__)

## Installation
1. clone the repo
2. install i3wm, picom, feh (for wallpaper), rofi. 
3. 
		cd i3-plasma
		cp -R ./* ~/.config/
		systemctl mask plasma-kwin_x11.service --user
		systemctl enable i3-plasma --user

## Other nice things to improve the experience
Go into the Settings app
Shrotcuts > Plasma
Find the setting that is bound to $mod+Q and remove it. 

in "~/Wallpaper", a file named wallpaper.jpg will be used as the wallpaper. 
   
