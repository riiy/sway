## install requirements

``` shell
yay -S alacritty rofi fzf clipboard grim grimshot mako greenclip

```

## install

``` shell
git clone git@github.com:riiy/sway ~/.config/sway
```

## after install

``` shell
md -p ~/.config/alacritty && cd ~/.config/alacritty && ln -s ../sway/alacritty 
cd ~/.config/ && ln -s ../greenclip.toml 
```
