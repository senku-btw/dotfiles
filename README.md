# dotfiles

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/yourusername/dotfiles/graphs/commit-activity)
[![CI Pipeline](https://img.shields.io/badge/CI-Passing-brightgreen.svg)]()


A robust, pristine, and enterprise-grade configuration repository for development environments. 

This repository automates the provisioning, symlinking, and management of personalised system configurations, shell environments, and developer tools.

---

## 🚀 Quick Start

To provision a fresh machine with these dotfiles, execute the following command:

```bash
git clone --recursive https://github.com/senku-btw/dotfiles.git

cd ~$HOME/.dotfiles

```

## 📦 System Architecture & Development Stack

| Component | Technology | Description |
|:-:	|:-:	|:-:	|
| Terminal Emulator | Foot | GPU-accelerated terminal configurations |
| Multiplexer	| tmux | Session persistence and window management |
|   	|   	|   	|

## 📂 Repository Structure

```
  .dotfiles/
  ├── .github/               # CI/CD workflows for linting and testing
  ├── config/                # XDG compatible application configurations
  │   ├── alacritty/         # Terminal settings
  │   ├── nvim/              # Neovim configuration (Lua)
  │   └── tmux/              # Tmux session configurations
  ├── home/                  # Global home directory configuration files
  │   ├── .zshrc             # Shell runcom
  │   ├── .gitconfig         # Global Git configuration
  │   └── .zshenv            # Environment variables
  └── LICENSE                # Repository license
```
## License

This repository is open-source software licensed under the MIT License. See the LICENSE file for more details.
