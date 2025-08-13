# My Dotfiles

Welcome to my **dotfiles repository**, which contains the configuration files for my personal Arch Linux setup.  
These files reflect my workflow using **Hyprland**, **Fish shell**, **Kitty terminal**, and **Caelestia shell utilities**.

> ⚡ **Note:** These configs are tailored to my workflow. Some paths or settings may need adjustments on other systems.


## About

I use this repository to manage my system configurations with [GNU Stow](https://www.gnu.org/software/stow/), which allows easy symlinking and version control.  

Key aspects of my setup:

- **OS:** Arch Linux  
- **Window Manager:** Hyprland  
- **Shell:** Fish shell with custom scripts and functions  
- **Terminal:** Kitty terminal with transparency, cursor effects, and Nerd Fonts  
- **Prompt:** Starship  
- **Utilities:** Caelestia scripts for workspace and system management  

---

## .config/
``` txt
.
├── btop -> /home/jaber/.local/share/caelestia/btop
├── caelestia
│   ├── hypr-user.conf
│   └── hypr-vars.conf
├── cava
│   ├── config
│   └── shaders
│       ├── bar_spectrum.frag
│       ├── northern_lights.frag
│       ├── pass_through.vert
│       ├── spectrogram.frag
│       └── winamp_line_style_spectrum.frag
├── dconf
│   └── user
├── fastfetch -> /home/jaber/.local/share/caelestia/fastfetch
├── fish -> /home/jaber/.local/share/caelestia/fish
├── foot -> /home/jaber/.local/share/caelestia/foot
├── hypr -> /home/jaber/.local/share/caelestia/hypr
├── kate-externaltoolspluginrc
├── katerc
├── katevirc
├── kdeglobals
├── kde.org
│   ├── UserFeedback.org.kde.dolphin.conf
│   └── UserFeedback.org.kde.kate.conf
├── kitty
│   └── kitty.conf
├── starship.toml -> /home/jaber/.local/share/caelestia/starship.toml
└── uwsm -> /home/jaber/.local/share/caelestia/uwsm
```

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/JaberChowdhury/dotfiles.git ~/dotfiles
cd ~/dotfiles
