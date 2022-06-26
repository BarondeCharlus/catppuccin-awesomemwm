<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/catppuccin/awesomewm">AwesomWM</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/awesomewm/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/awesomewm?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/awesomewm/issues"><img src="https://img.shields.io/github/issues/catppuccin/awesomewm?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/awesomewm/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/awesomewm?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/demo.png"/>
</p>

## Usage

1. Clone this repository locally
```shell
mkdir -p $HOME/.config/awesome/themes
git clone https://github.com/catppuccin/awesomewm
mv awesomewm/themes/catppuccin .config/awesome/themes/
```
2. Select theme in your `rc.lua`
```shell
# $HOME/.awesome/rc.lua
# […]
local chosen_theme = "catppuccin"
local theme_path = string.format("%s/.config/awesome/themes/%s/theme.lua", os.getenv("HOME"), chosen_theme)
beautiful.init(theme_path)
# […]
```

## 💝 Thanks to

- [Kaderovski](https://github.com/kaderovski)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
