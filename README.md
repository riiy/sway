## install requirements

``` shell
yay -S kitty alacritty rofi wofi fzf grim grimshot mako greenclip clipboard wl-clipboard xdg-utils cliphist adobe-source-han-sans-cn-fonts thunar

```

## install

``` shell
git clone git@github.com:riiy/sway ~/.config/sway
```

## after install

``` shell
md -p ~/.config/kitty && cd ~/.config/kitty && ln -s ../sway/kitty_conf kitty.conf && ln -s ../sway/kitty_theme theme.conf 
md -p ~/.config/mako && cd ~/.config/mako && ln -s ../sway/mako_config config
md -p ~/.config/wofi && cd ~/.config/wofi && ln -s ../sway/wofi_style.css style.css && ln -s ../sway/wofi_config config
md -p ~/.config/alacritty && cd ~/.config/alacritty && ln -s ../sway/alacritty.toml
```

## others


### install yay

``` shell
sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay-bin.git && cd yay-bin && makepkg -si
```

### install shadowsocks-rust

``` shell
yay -S shadowsocks-rust

cd /etc/shadowsocks-rust/ && sudo mv config_ext_rust.json.example config.json && vim config.json
sudo systemctl status shadowsocks-rust@config.service
```

### install chrome

``` shell
yay -S google-chrome
# 设置字体为 Source Han Sans CN
```

### install fcitx5
