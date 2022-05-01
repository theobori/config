# linux config

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
or just restart your terminal

5. If you wanna use `st` instead of `urxvt`
```bash
git clone https://git.suckless.org/st
cd st
sudo make clean install
```
and you can replace the lines in `config.h` by ones in `st_config.txt`