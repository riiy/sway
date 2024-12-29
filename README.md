## install requirements

``` shell
yay -S kitty wofi fzf clipboard grim grimshot mako greenclip

```

## install

``` shell
git clone git@github.com:riiy/sway ~/.config/sway
```

## after install

``` shell
md -p ~/.config/kitty && cd ~/.config/kitty && ln -s ../sway/kitty_conf kitty.conf && ln -s ../sway/kitty_theme theme.conf 
cd ~/.config/ && ln -s ../greenclip.toml 
md -p ~/.config/mako && cd ~/.config/mako && ln -s ../sway/mako_config config
md -p ~/.config/wofi && cd ~/.config/wofi && ln -s ../sway/wofi_style.css style.css && ln -s ../sway/wofi_config config
```
