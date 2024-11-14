# Hyprland Dotfiles

![image](./preview.png)

This repository contains configuration files (dotfiles) for setting up a custom Hyprland environment on Wayland. The configuration focuses on a modern, efficient, and visually cohesive setup, optimized for functionality and aesthetics.

## Features
- **Hyprland Customization**: Includes configurations for bar layout, themes, keyboard shortcuts, and etc.
    - OS: Arch Linux
    - WM: Hyprland
    - Shell: zsh
    - Terminal: kitty
    - Bar: waybar
    - Application Launcher: rofi

## Installation
#### 1. Install Dependencies
You may need to install some Hyprland components and optional packages. Use the following command on Arch-based systems:
```bash
sudo pacman -S hyprland waybar hyprpaper wlogout rofi kitty fastfetch thunar
```

#### 2. Clone the Repository
Clone this repository to your home directory:
```bash
git clone https://github.com/gilangarya01/hyprland-dotfiles.git
cd ~/hyprland-dotfiles
```

#### 3. Copy or Rsync Dotfiles
```bash
cp -r ./ ~/
# or
rsync -av ./ ~/
```
Log out and log back in, or restart your system.


