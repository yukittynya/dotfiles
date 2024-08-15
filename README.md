
# 🌸 Dotfiles :3

Here are my hyprland dotfiles based off the wallpaper from a lofi playlist, "[Somewhere Nowhere](https://youtu.be/eAXdSkBMQAQ)". I hope you enjoy it :3

## Overview
The cuties that make up this environment 
- **Distro:** Arch Linux :3
- **WM:** Hyprland
- **Status Bar:** Waybar
- **Terminal:** Kitty
- **Shell:** ZSH
- **Neovim:** NvChad

## Dependencies

Make sure to install these otherwise things won't work duhhh :3

### Packages
```yay -S hyprland waybar hyprpaper dunst pavucontrol brightnessctl zsh kitty rofi eww nitch pywal-16-colors nautilus grim slurp neovim```

### Fonts

- [Martian Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/MartianMono.zip)
- [Jetbrains Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/JetBrainsMono.zip)
- [Iosevka Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Iosevka.zip)

### Install

Run this to get the goods :o

```git clone https://github.com/yukittynya/dotfiles.git```

Place the folders in a structure like this! Note: you will have to create .fonts and put the fonts in that directory then run ```fc-cache -fv```

```
~/
├── .config/
│   ├── dunst
│   ├── eww
│   ├── hypr
│   ├── kiitty
│   ├── waybar
│   └── zsh
├── .fonts/
│   ├── MartianMono
│   ├── Jetbrains
│   └── Iosevka
├── .wallpapers/
│   ├── somewhere_nowhere.jpg
│   └── *
└── .zshenv
```
## Post Install

Firstly I make use of pywal to get the colors for themeing based off my current wallpaper. Run this command to get it functioning, replace '~/.wallpapers/somewhere_nowhere.jpg' with any path to an image of your choice :3

```wal -i ~/.wallpapers/somewhere_nowhere.jpg```

If you would like to have user directories then use xdg-user-dirs!

```yay -S xdg-user-dirs``` then run ```xdg-user-dir```

For Neovim I use [NvChad](https://nvchad.com/), install it with ```git clone https://github.com/NvChad/starter ~/.config/nvim && nvim```
## Screenshots

![](https://github.com/yukittynya/dotfiles/blob/master/screenshots/one.png)
![](https://github.com/yukittynya/dotfiles/blob/master/screenshots/two.png)
![](https://github.com/yukittynya/dotfiles/blob/master/screenshots/three.png)
![](https://github.com/yukittynya/dotfiles/blob/master/screenshots/four.png)
