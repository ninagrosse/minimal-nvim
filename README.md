# minimal-nvim

A minimal Neovim config

This config only sets some sane defaults and keymaps. It is designed to work offline, so it does not include a plugin manager.
The only manually included plugin is [fzf-lua](https://github.com/ibhagwan/fzf-lua).

My default Neovim config can be found at [ninagrosse/lazyvim-config](https://github.com/ninagrosse/lazyvim-config)

## Installation

Clone the repo

```shell
git clone git@github.com:ninagrosse/minimal-nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/minimal-nvim
```

Start Neovim with this config

```shell
NVIM_APPNAME=minimal-nvim nvim
```
