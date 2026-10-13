# 🌸 Mis dotfiles ✨

![made with love](https://img.shields.io/badge/made%20with-💖-ff69b4?style=for-the-badge)
![arch](https://img.shields.io/badge/Arch-Linux-87CEEB?style=for-the-badge&logo=archlinux&logoColor=white)
![hyprland](https://img.shields.io/badge/Hyprland-end--4-ffb6c1?style=for-the-badge)

## 🎀 Sobre este repo

> Mi configuración de Arch Linux, hecha con mucho amor 🍓

Basada en [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland) con mis propios ajustes.

## 🖥️ Mi setup

| | |
|---|---|
| **OS** | Arch Linux |
| **WM** | Hyprland |
| **Shell** | fish + starship |
| **Terminal** | kitty |
| **Equipo** | Dell Latitude E7250 |

## 📦 Qué incluye

- `hypr/` — configuración de Hyprland (mis cambios están en `custom/`)
- `illogical-impulse/` y `matugen/` — shell y colores de end-4
- `kitty/`, `foot/`, `fish/`, `starship.toml` — terminal y shell
- `fastfetch/`, `cava/`, `fuzzel/`, `wlogout/`, `Kvantum/`, `gtk-*` — apariencia y utilidades
- `pkglist.txt`, `aur-pkglist.txt`, `flatpak-list.txt`, `code-extensions.txt` — listas de paquetes

## 🔁 Restaurar

1. Instala end-4 siguiendo su [guía oficial](https://github.com/end-4/dots-hyprland).
2. Clona este repo como bare y aplica los dotfiles:

```fish
git clone --bare https://github.com/UP240594/Mis_dotfiles.git $HOME/.dotfiles
alias dot 'git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
funcsave dot
dot checkout        # si hay conflictos, respalda o mueve los archivos existentes
dot config --local status.showUntrackedFiles no
```

3. Paquetes:

```fish
sudo pacman -S --needed - < ~/.config/pkglist.txt
yay -S --needed - < ~/.config/aur-pkglist.txt
xargs flatpak install -y < ~/.config/flatpak-list.txt
xargs -n1 code --install-extension < ~/.config/code-extensions.txt
```

## 🌷 Notas

Los archivos que matugen regenera con cada wallpaper (colores de GTK, fuzzel, hyprlock) no están en el repo a propósito.
