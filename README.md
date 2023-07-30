# Telescope-rtfm

Telescope-rtfm shamelessly takes the help_tags picker and uses it with tmux new-window.

## Requires

Must have tmux installed

## Install

Install the plugin

```lua
Plug('maladroitthief/telescope-rtfm.nvim')
```

Add the following to the telescope config

```lua
require("telescope").load_extension "rtfm"
```

## Usage

```vim
:Telescope rtfm
```
