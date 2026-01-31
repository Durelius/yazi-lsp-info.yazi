
# yazi-lsp-info.yazi

Show the status of LSP reports changes as linemode in the file list.



## Requirements

The nvim side of the plugin: [yazi-lsp-info.nvim](https://github.com/Durelius/yazi-lsp-info.nvim)

## Installation

```sh
ya pkg add durelius/yazi-lsp-info
```


## Setup

Add the following to your `~/.config/yazi/init.lua`:

```lua
require("yazi-lsp-info"):setup()
```

And register it as fetchers in your `~/.config/yazi/yazi.toml`:

```toml
[[plugin.prepend_fetchers]]
id  = "yazi-lsp-info"
url = "*"
run = "yazi-lsp-info"

[[plugin.prepend_fetchers]]
id  = "yazi-lsp-info"
url = "*/"
run = "yazi-lsp-info"
```
