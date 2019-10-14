# Glorious Dotfiles

## Details
+ **OS**: I use Arch, btw
+ **WM**: AwesomeWM
+ **Terminal Emulators**: kitty, urxvt-pixbuf, xterm
+ **Compositor**: compton-tryone-git
+ **File Manager**: nemo
+ **Launcher**: rofi-git
+ **Editor**: neovim, atom
+ **Browser**: firefox
+ **Music Player**: ncmpcpp, mpd, mpc

# Floppy - An AwesomeWM Setup

## NEW FEATURES!
+ **Brightness and Volume OSDs**
+ **Sidebar rofi changed from searching apps to searching the web**
+ **Dynamic Wallpaper Module**
  - Wallpaper changes based on time. You can modify it here `$HOME/.config/awesome/module/wallchange.lua`
  - Wallpapers are in `$HOME/.config/awesome/theme/wallpapers`
+ **BUGS. A LOT OF BUGS.**

## Theme Preview  

| Floppy | Preview |
| --- | --- |
| Desktop | ![Screenshot](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/desktop.png) |
| Dirty | ![Screenshot](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/dirty.png)   |
| Dashboard | ![Screenshot](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/dashboard.png) |
| Web Search | ![Screenshot](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/rofi-searchweb.gif) |
| Dashboard in Action | ![GIF](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/dashboardinaction.gif) |
| App Dashboard | ![Screenshot](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/application-dashboard.png) |
| OSDs | ![GIF](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/OSDs.gif) |
| Exit Screen | ![GIF](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/exit-screen.png) |
| Day Wallpaper | ![wall](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/day-wallpaper.jpg)  
| Night Wallpaper | ![wall](https://github.com/ilovecookieee/Glorious-Dotfiles/blob/master/screenshots/night-wallpaper.jpg)  


## Dependencies
Here is a complete list of dependencies needed for making these AwesomeWM setup to work.
If you notice that something is missing, please open an issue so I can add the dependency to this table.

**Make sure that you installed them before using this setup**  

| Dependency | Description | Why/Where is it needed? |
| --- | --- | --- |
| `awesome-git` | Window manager | yeah awesome |
| `rofi-git` | Window switcher, application launcher and dmenu replacement | Application launcher |
| `Compton-tryone` | A compositor for X11 | compositor with kawase-blur |
| `blueman` | Manages bluetooth | For bluetooth widgets |
| `xfce4-settings-manager` | Manages basic settings | System Settings |
| `xfce4-power-manager` | Manages battery/power settings | Power Settings |
| `acpi` | Show battery status and other ACPI info | Charger notifications |
| `pulseaudio`, `libpulse` | Sound system | Volume widgets and keybinds |
| `redshift` | Controls screen temperature | Night mode command |
| `mpd` | Server-side application for playing music | Music widgets |
| `mpc` | Minimalist command line interface to MPD | Music widgets |
| `maim` | Takes screenshots (improved `scrot`) | Screenshot keybinds |
| `feh` | Image viewer and wallpaper setter | Screenshot previews, wallpapers |
| `xorg-xwininfo` | Window information utility for X | it just works |
| `python3`| an interpreted, interactive, object-oriented programming language | Web-search Backend |



##### Monospace
+ **[Iosevka Custom](https://github.com/elenapan/dotfiles/)**

##### Sans
+ **Google Sans**
+ **San Francisco Display**

#### Installation
+ Copy `Glorious-Dotfiles/config/awesome` to `$HOME/.config/`
+ Reload Awesome

# Got a problem? Just open an issue ![here](https://github.com/ilovecookieee/Glorious-Dotfiles/issues/new).
#### Suggestion? If you have any suggestion on how to improve this setup, please open an issue ![here](https://github.com/ilovecookieee/Glorious-Dotfiles/issues/new).



**Special thanks**
+ **PapyElGringo** for the awesome [material-awesome](https://github.com/PapyElGringo/material-awesome)
+ **pdonadeo** for the [rofi-web-search.py](https://github.com/pdonadeo/rofi-web-search)
+ **[elenapan](https://github.com/elenapan/dotfiles)**
+ **[addyfe](https://github.com/addy-dclxvi/almighty-dotfiles)**
+ **Myself, for not giving up**
