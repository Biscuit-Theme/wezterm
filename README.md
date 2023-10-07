# [WezTerm](https://wezfurlong.org/wezterm/)
> 🍪 Biscuit theme for Wezterm

### Install (Git)
If you have Git installed on your system, you can simply use the `git clone` command to install this theme:
```bash
git clone https://github.com/biscuit-theme/wezterm
``` 

### Installation (Manual)
On the off chance that you are not familar with Git, you may download the [.ZIP File](https://github.com/biscuit-theme/wezterm/archive/master.zip), and unzip it.

### Activation
1. Move the `./colors/` directory to the WezTerm config directory:
  ```bash
  mkdir -p $HOME/.config/wezterm/ # Assuming it doesn't already exist
  mv ./colors/ $HOME/.config/wezterm/
  ```
2. Modify the wezterm.lua file (`$HOME/.config/wezterm/wezterm.lua`)
  ```lua
  return {
    color_scheme = "biscuit-dark", # or biscuit-light (sourced from ./colors/)
    ## Optional settings
    tab_bar_at_bottom = true,
    use_fancy_tab_bar = false,
    window_decorations = "RESIZE"
  }
  ```
## Team
This theme port is actively maintained by these amazing individuals:
| [![Letrad](https://avatars.githubusercontent.com/u/134692905?s=70)](https://github.com/letrad) |
| ------------------------------------------------------------------------------------------------ |
| [Letrad](https://github.com/letrad)                                                            |


## License

[MIT License](./LICENSE)

