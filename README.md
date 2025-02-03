```
  ____             _     __                _ 
|  _ \  __ _ _ __| | __/ _| ___ _ __   __| |
| | | |/ _` | '__| |/ / |_ / _ \ '_ \ / _` |
| |_| | (_| | |  |   <|  _|  __/ | | | (_| |
|____/ \__,_|_|  |_|\_\_|  \___|_| |_|\__,_|
```
An simple hyprland dotfiles for arch linux and arch based distro
Made by @Flasherxgapple aka Fendi

![screenshot of darkfend dotfiles](/Hyprland-overview.png)

Another screenshot in config directory of this repository

Dependencies:
- git - clone the repository
* kitty/alacritty - Terminal with transparency support
+ hyprland - Wayland tiling window manager with various effect and features
- xdg-desktop-portal-hyprland - Screensharing support
- waybar - Panel/bar for wayland
- grim & grimshot - Screenshot utility
- yay - Arch linux AUR helper
- wofi & rofi - App launcher and runner
- wlogout - Logout menu
- swaylock & swaylock-effects - Lockscreen utility
- chiplist - clipboard utility
- network-manager-applet - Network manager
- pipewire & wireplumber - Audio support
- blueman - Bluetooth manager
- dolphin - File manager
- firefox - Web browser
- pavucontrol & pamixer - Volume control
- cava - Audio visualizer
- swww & waypaper - Wallpaper utility
- swaync/mako - Notification daemon
- btop - system monitor
- noto-fonts-emoji - Icon fonts
- ttf-jetbrains-mono-nerd - Main fonts

first install yay:
```
sudo pacman -Syu
sudo pacman -S --needed base-devel git
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```
install the dependencies:
```
yay -Syu kitty swaync waybar swww waypaper wofi wlogout xdg-desktop-portal-hyprland grim grimshot btop pamixer pavucontrol swaylock ttf-jetbrains-mono-nerd noto-fonts-emoji network-manager-applet swaylock-effects sddm pipewire wireplumber chiplist hyprland cava blueman dolphin firefox
```
