<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18&height=230&section=header&text=Mis%20dotfiles&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Arch%20Linux%20%2B%20Hyprland&descAlignY=58&descSize=20" width="100%" alt="banner"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=F5A9C8&center=true&vCenter=true&width=520&lines=Hecho+con+mucho+cari%C3%B1o;Arch+Linux+%2B+Hyprland;Configurado+poco+a+poco;Mi+cuaderno+en+blanco+listo+para+usarse" alt="typing"/>

<br>

⸜(｡˃ ᵕ ˂)⸝ ♡ ⸜(｡˃ ᵕ ˂)⸝ ♡ ⸜(｡˃ ᵕ ˂)⸝ ♡ ⸜(｡˃ ᵕ ˂)⸝

<br>

![arch](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)
![hyprland](https://img.shields.io/badge/Hyprland-58E1FF?style=for-the-badge&logo=hyprland&logoColor=black)
![end-4](https://img.shields.io/badge/based_on-end--4-F5A9C8?style=for-the-badge)
![fish](https://img.shields.io/badge/shell-fish-87CEEB?style=for-the-badge)

</div>

<br>

## (≧◡≦) ♡ Sobre este repo

> ✧ Mi configuración de Arch Linux, armada con mucho amor ✧
> (ᵔᴥᵔ) ya sabes, de esas cosas que uno ajusta "solo un ratito más"... (⁠◍⁠•⁠ᴗ⁠•⁠◍⁠)

Está basada en [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland) con mis propios ajustes ٩(◕‿◕)۶

<br>

## ♪ (ﾉ◕ヮ◕)ﾉ*:･ﾟ✧ Mi setup

<div align="center">

| ✧ | ♡ |
|:---:|:---:|
| **OS** | Arch Linux |
| **WM** | Hyprland |
| **Shell** | fish + starship |
| **Terminal** | kitty |
| **Equipo** | Dell Latitude E7250 |
| **Colores** | matugen (Material You) |

</div>

<br>

## (๑•̀ㅂ•́)و✧ Capturas

<div align="center">

(っ◔◡◔)っ ♡ *aquí va una captura o un GIF de mi escritorio* ♡

<!-- ![rice](screenshots/rice.gif) -->

</div>

<br>

## ⸜(｡˃ ᵕ ˂)⸝ ✧ Qué incluye

```text
(◕‿◕)  hypr/             Hyprland (mis cambios están en custom/)
(≧◡≦)  illogical-impulse/ y matugen/   shell y colores de end-4
(ﾉ´ヮ`)ﾉ kitty/ foot/ fish/ starship.toml   terminal y shell
(๑>◡<๑) fastfetch/ cava/ fuzzel/ wlogout/ Kvantum/ gtk-*   apariencia
(｡•̀ᴗ-)✧ pkglist / aur-pkglist / flatpak-list / code-extensions   paquetes
```

<br>

## ♡ ⸜(｡˃ ᵕ ˂)⸝ Cómo restaurarlo

**1.** Instala end-4 con su [guía oficial](https://github.com/end-4/dots-hyprland) (づ｡◕‿‿◕｡)づ

**2.** Clona este repo como bare y aplica los dotfiles:

```fish
git clone --bare https://github.com/UP240594/Mis_dotfiles.git $HOME/.dotfiles
alias dot 'git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
funcsave dot
dot checkout        # si hay conflictos, respalda o mueve los archivos existentes
dot config --local status.showUntrackedFiles no
```

**3.** Paquetes ✧(≖ ◡ ≖✿)

```fish
sudo pacman -S --needed - < ~/.config/pkglist.txt
yay -S --needed - < ~/.config/aur-pkglist.txt
xargs flatpak install -y < ~/.config/flatpak-list.txt
xargs -n1 code --install-extension < ~/.config/code-extensions.txt
```

<br>

## (・ω・)ノ Notas

- Los colores que matugen regenera con cada wallpaper (GTK, fuzzel, hyprlock) no están en el repo a propósito (￣ω￣)
- Si algo se rompe al restaurar... respira y revisa `dot status` (´･ω･`)

<br>

<div align="center">

(ﾉ◕ヮ◕)ﾉ*:･ﾟ✧ gracias por pasar por aquí ✧ﾟ･:
