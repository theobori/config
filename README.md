# linux config

## About

This repository every contains configuration file required for my environment.

## How to build and run ?

1. Install the dependencies
    **Debian / Ubuntu**
```bash
sudo apt install fish tmux rxvt-unicode
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