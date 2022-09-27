# DX (Developer Experience)
Suite of scripts to make getting up-and-running on different systems easier

## Hierarchy
- dx
  - dx-cli
  - dx-os
    - dx-os-mac
    - dx-os-linux
      - dx-os-linux-arm

## Purpose
- dx-cli
> Install cross-platform UNIX/LINUX cli commands (brew & zsh commands)

- dx-os
> Cross-OS config (eg. brew), crontab for Obsidian sync<->git parity, etc.

- dx-os-mac
> Mac specific config (eg. can only use brew cask and app store on Mac; keyrepeat config OS specific)

- dx-os-linux
> Install tmux, lunarvim, neovim, and other dependencies

- dx-os-linxu-arm
> ARM specific installs (eg. LunarVim install script doesn't work as-is on ARM)
