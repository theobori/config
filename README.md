# linux environment configuration (de, wm, lockscreen, etc..)

## About

This repository every contains configuration file required for my environment.

## How to build and run ?

1. Install the dependencies
    **Debian / Ubuntu**
```bash
sudo apt install fish tmux rxvt-unicode xclip
```

**Arch Linux**
```bash
sudo pacman -S fish tmux rxvt-unicode xclip
```

2. Install the font(s)
    - Font name: **`Comic Code`**

3. Copy the files
    - A script is available, just run
```bash
bash scripts/install.sh
```

4. Reload the current configuration with **`xrdb`**
```bash
xrdb $HOME/.Xresources
```

5. For suckless tools configuration, there are git diff files in `suckless_config/`

6. Using https://github.com/joestandring/dwm-bar as status bar