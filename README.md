# alacritty-config

## Usage

```sh
git clone https://github.com/yandy/alacritty-config.git ~/.config/alacritty
```

## 平台特定配置

将对应平台的配置文件链接到 `os-specific.toml`

- Windows: `New-Item -ItemType SymbolicLink -Path ./os-specific.toml -TargetPath ./_windows.toml`
- Linux: `ln -s ./_linux.toml ./os-specific.toml`
