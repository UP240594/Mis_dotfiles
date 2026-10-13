<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1033,45:7c3aed,100:e879f9&height=250&section=header&text=Mis%20dotfiles&fontSize=66&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=i%20use%20arch%20btw&descAlignY=60&descSize=22" width="100%" alt="banner"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=C084FC&center=true&vCenter=true&width=620&lines=Arch+Linux+%2B+Hyprland;Hecho+con+mucho+cari%C3%B1o;Configurado+poco+a+poco;Mi+cuaderno+en+blanco+listo+para+usarse;I+use+Arch+btw" alt="typing"/>

<br><br>

⸜(｡˃ ᵕ ˂)⸝ ♡ ⸜(｡˃ ᵕ ˂)⸝ ♡ ⸜(｡˃ ᵕ ˂)⸝ ♡ ⸜(｡˃ ᵕ ˂)⸝ ♡ ⸜(｡˃ ᵕ ˂)⸝

<br><br>

<img src=".config/readme-assets/arch.svg" width="720" alt="fastfetch animado"/>

<br><br>

![arch](https://img.shields.io/badge/Arch_Linux-7C3AED?style=for-the-badge&logo=archlinux&logoColor=white&labelColor=1a1033)
![hyprland](https://img.shields.io/badge/Hyprland-A78BFA?style=for-the-badge&logo=hyprland&logoColor=white&labelColor=1a1033)
![end-4](https://img.shields.io/badge/based_on-end--4-C084FC?style=for-the-badge&labelColor=1a1033)
![fish](https://img.shields.io/badge/shell-fish-E879F9?style=for-the-badge&labelColor=1a1033)
![kitty](https://img.shields.io/badge/term-kitty-F5D0FE?style=for-the-badge&labelColor=1a1033)

</div>

<br>

## ⸜(｡˃ ᵕ ˂)⸝ ♡ Sobre este repo

> ✧ Mi configuración de Arch Linux, no soy experta en arch, pero queria experimentar con hacer un readme muy lindo y asterik, este repo me ayuda a tener las aplicaciones que uso en arch, para no tener que instalarlas desde cero cada que reinstalo arch en dado caso -.-. Aun asi espero q te guste ✧
> (ᵔᴥᵔ) de esas cosas que uno ajusta "solo un ratito más"... (⁠◍⁠•⁠ᴗ⁠•⁠◍⁠)

Basada en [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland) con mis propios ajustes ٩(◕‿◕)۶

<div align="center">

⋆˚✧ ─────────── ♡ ─────────── ✧˚⋆

</div>

## (≧◡≦) ✧ Mi setup

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

<div align="center">

⋆˚✧ ─────────── ♡ ─────────── ✧˚⋆

</div>

## (๑•̀ㅂ•́)و✧ Capturas

<div align="center">

(っ◔◡◔)っ ♡ aquí va una captura o un GIF de mi escritorio ♡

<img src="screenshots/rice.gif" width="720" alt="mi escritorio"/>

</div>

<div align="center">

⋆˚✧ ─────────── ♡ ─────────── ✧˚⋆

</div>

## ଘ(੭ˊᵕˋ)੭ ✧ Qué incluye

```text
(◕‿◕)    hypr/                       Hyprland (mis cambios están en custom/)
(≧◡≦)    illogical-impulse/ matugen/ shell y colores de end-4
(ﾉ´ヮ`)ﾉ  kitty/ foot/ fish/ starship  terminal y shell
(๑>◡<๑)  fastfetch/ cava/ fuzzel/    apariencia y utilidades
         wlogout/ Kvantum/ gtk-*
(｡•̀ᴗ-)✧  pkglist, aur-pkglist,       listas de paquetes
         flatpak-list, code-extensions
```

<div align="center">

⋆˚✧ ─────────── ♡ ─────────── ✧˚⋆

</div>

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

<div align="center">

⋆˚✧ ─────────── ♡ ─────────── ✧˚⋆

</div>

## (・ω・)ノ Notas

- Los colores que matugen regenera con cada wallpaper (GTK, fuzzel, hyprlock) no están en el repo a propósito (￣ω￣)
- Si algo se rompe al restaurar... respira y revisa `dot status` (´･ω･`)

<br>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=2500&pause=1200&color=E879F9&center=true&vCenter=true&width=520&lines=Gracias+por+pasar+por+aqu%C3%AD;Que+tu+escritorio+siempre+quede+bonito;Hasta+la+pr%C3%B3xima" alt="gracias"/>

⸜(｡˃ ᵕ ˂)⸝ ♡ (ﾉ◕ヮ◕)ﾉ ♡ ⸜(｡˃ ᵕ ˂)⸝

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1033,45:7c3aed,100:e879f9&height=150&section=footer" width="100%" alt="footer"/>

</div>
