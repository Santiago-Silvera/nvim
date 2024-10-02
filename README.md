# Personal NeoVim Configuration
This is a repository to make the installation of my NeoVim configuration easier.

## Installing NeoVim
### Pre-built archives

The [Releases](https://github.com/neovim/neovim/releases) page provides pre-built binaries for Linux systems.

```sh
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux64.tar.gz
```

Then add this to your shell config (`~/.zshrc`):
```
export PATH="$PATH:/opt/nvim-linux64/bin"
source ~/.zshrc
```

## Install
To install , ``cd`` into your configuration directory and run the command:
```
git clone https://github.com/Santiago-Silvera/nvim
```

After cloning, just open `nvim` and lazy package manager will install all dependencies for you.
It is recommended that you have installed Node.js, gcc and ripgrep. Also running `:checkhealth` is a good idea.



---
Thank you :) 
