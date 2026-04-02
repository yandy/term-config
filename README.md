# alacritty-config

## Clone this repository

```sh
git clone https://github.com/yandy/alacritty-config.git ~/.config/alacritty
```

## 主要特性

- 选中即复制
- `Ctrl + V` 粘贴

#### vim 模式(非tmux环境)

| 快捷键 | 作用 |
|------|--------|
|`Ctrl + Shift + Space`| 进入vim 模式|
|`i`| 退出vim 模式|
|`v`| 开始选择文本|
|`Esc`| 取消选择文本|
|`y`| 复制选中的文本|

其他参考： [vi 光标操作](./README-vi.md)


## 平台特定配置

将对应平台的配置文件链接到 `os-specific.toml`

- Windows: `New-Item -ItemType SymbolicLink -Path ./os-specific.toml -TargetPath $PWD/_windows.toml`
- Linux: `ln -s $(pwd)/_linux.toml ./os-specific.toml`

## tmux

#### 配置

将 `tmux.conf` 链接到 `~/.tmux.conf`

- Windows: `New-Item -ItemType SymbolicLink -Path $HOME/tmux.conf -TargetPath $PWD/_windows.tmux.conf`
- Linux: `ln -s $(pwd)/tmux.conf ~/.tmux.conf`

#### [使用](./README-tmux.md)
