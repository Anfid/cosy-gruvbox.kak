# base16-gruvbox.kak
Gruvbox colorscheme for Kakoune editor. Based on Vim's gruvbox colorscheme.

## Installation

### Via [plug.kak](https://github.com/andreyorst/plug.kak)

```kak
plug "Anfid/cosy-gruvbox.kak" noload do %{
    mkdir -p $HOME/.config/kak/colors
    find $PWD -type f -name "*.kak" -exec ln -sf {} $HOME/.config/kak/colors/ \;
} config %{
    colorscheme cosy-gruvbox
}
```

### Without plugin manager

Place a symbolic link or copy `cory-gruvbox.kak` to your `colors` folder at Kakoune configuration folder.

## Special thanks

Thanks [@andreyorst](https://github.com/andreyorst) for creating base16-gruvbox colorscheme, from which this colorscheme was forked.
