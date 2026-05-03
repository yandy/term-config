# term-config

## Setup

```sh
git clone https://github.com/yandy/term-config.git ~/.config/ghostty
sudo pacman -S ghostty
```

## Features

[reference](https://ghostty.org/docs/features)

补充特性：

- 智能 `Ctrl-C`，当有内容选中的时候为"复制到剪切板"，否则为 "中断信号"

## Keymaps

**list all keymaps**

```sh
ghostty +list-keybinds
```
**main keymaps**
```
ctrl  + ,                             open_config
ctrl  + shift + ,                     reload_config
ctrl  + shift + p                     toggle_command_palette

ctrl  + shift + n                     new_window
ctrl  + enter                         toggle_fullscreen

ctrl  + shift + t                     new_tab
ctrl  + tab                           next_tab
ctrl  + shift + tab                   previous_tab
ctrl  + shift + w                     close_tab:this

ctrl  + shift + o                     new_split:right
ctrl  + shift + e                     new_split:down
ctrl  + shift + enter                 toggle_split_zoom
ctrl  + alt   + arrow_down            goto_split:down
ctrl  + alt   + arrow_left            goto_split:left
ctrl  + alt   + arrow_right           goto_split:right
ctrl  + alt   + arrow_up              goto_split:up

ctrl  + shift + f                     start_search
escape                                end_search

ctrl  + c                             copy_to_clipboard:mixed
ctrl  + v                             paste_from_clipboard
ctrl  + alt   + v                     paste_from_selection

shift + page_down                     scroll_page_down
shift + page_up                       scroll_page_up
```
