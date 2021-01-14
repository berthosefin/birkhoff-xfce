## Preview
![scrot](https://raw.githubusercontent.com/berthosefin/birkhoff-xfce/master/scrot.png)

## Details
- **Display Server** X11
- **Display Manager** LightDM
- **Greeter** LightDM GTK Greeter
- **Desktop Environment** xfce4.14
- **WM** Xfwm4
- **Launcher** Rofi
- **Panel** Xfce4-panel
- **GTK Theme** Arc
- **Icons** Arc
- **Cursor** Bibata
- **GTK Fonts** Opensans, Vollkorn, Fira Code
- **File Manager** Thunar, Nautilus
- **Web Browser** Firefox
- **Task Manager** Xfce4-tasmanager, HTOP
- **Image Viewer** Ristreto, Viewnior, Feh
- **Sound Mixer** PulseAudio
- **Terminal** Xfce4-terminal, Tilix
- **CLI Shell** ZSH
- **Archiver** XArchiver
- **Notification Daemon** Dunst
- **Graphic Editor** GIMP
- **CLI File Manager** Ranger
- **CLI Text Editor** Vim
- **GUI Text Editor** Mousepad, SublimeText
- **CLI Music Player** MPD, Ncmpcpp, Cava
- **GUI Music Player** Rhythmbox
- **Media Player** MPV, SMPlayer, VLC
- **Policy Kit Frontend** Gnome Polkit
- **Screenshooter** Xfce4-screenshooter

## Notes
- If you want to use this configuration, inspect the code before use.
- Install git
- Clone this repo `git clone --depth=1 https://github.com/berthosefin/xfce ~/.xfce`
- Deploy the dotfiles `cp -a ~/.xfce/. ~`
- Change the default CLI Shell `chsh $(whoami) -s /bin/zsh`
- If you find "birkhoff" in the configuration file, replace it with your own username.
- Edit some system configuration, example in ~/.xfce/.system
- Reboot
- Fix some errors
- Start working
