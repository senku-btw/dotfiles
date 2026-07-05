[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CI Pipeline](https://img.shields.io/badge/CI-Passing-brightgreen.svg)]()

# dotfiles

This repository automates the provisioning, symlinking, and management of personalised system configurations, shell environments, and developer tools.

> *“Simplicity is the ultimate sophistication.” — Leonardo da Vinci*

<br>

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
