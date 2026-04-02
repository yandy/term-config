# alacritty-config

## Clone this repository

```sh
git clone https://github.com/yandy/alacritty-config.git ~/.config/alacritty
```

## tmux 配置

将 `tmux.conf` 链接到 `~/.tmux.conf`

- Windows: `New-Item -ItemType SymbolicLink -Path $HOME/tmux.conf -TargetPath $PWD/_windows.tmux.conf`
- Linux: `ln -s $(pwd)/tmux.conf ~/.tmux.conf`


## 平台特定配置

将对应平台的配置文件链接到 `os-specific.toml`

- Windows: `New-Item -ItemType SymbolicLink -Path ./os-specific.toml -TargetPath $PWD/_windows.toml`
- Linux: `ln -s $(pwd)/_linux.toml ./os-specific.toml`
