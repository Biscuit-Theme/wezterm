<h3 align="center">
  <img src="https://raw.githubusercontent.com/Biscuit-Colorscheme/.github/main/assets/icon-dark-nobg.png" width="100"/><br/>
  Biscuit for <a href="https://wezfurlong.org/wezterm/">WezTerm</a>
</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/Biscuit-Colorscheme/.github/main/assets/color-cycle-light.png" alt="Biscuit palette" width="400" />
</p>

<!-- 
Insert Screenshot if Applicable 
---------------------------------
<p align="center">
  <img src="assets/screenshot.png"/>
</p>
---------------------------------
-->
### 📥 Installation
1. If you have Git installed on your system, you can simply use the `git clone` command to install this theme:
   ```bash
   git clone https://github.com/biscuit-colorscheme/wezterm
   ```
   
   Otherwise, on the off chance that you are not familar with Git, you may download the [.ZIP File](https://github.com/biscuit-theme/wezterm/archive/master.zip), and unzip it.

2. Move the `./colors/` directory to the WezTerm config directory:
    ```bash
    mkdir -p $HOME/.config/wezterm/ # Assuming it doesn't already exist
    mv ./colors/ $HOME/.config/wezterm/
    ```

### 📦 Activating
Once the necessary files in place, activating the **Biscuit Theme** is as simple as:
1. Modify the wezterm.lua file (`$HOME/.config/wezterm/wezterm.lua`)
  ```lua
  return {
    color_scheme = "biscuit-dark", -- or biscuit-light (sourced from ./colors/)
    -- Optional settings
    tab_bar_at_bottom = true,
    use_fancy_tab_bar = false,
    window_decorations = "RESIZE"
  }
  ```

### 💝 Thanks To
Thanks to all these amazing people for their work!
<!-- This does not render until you use the correct project name-->
<a href="https://github.com/biscuit-colorscheme/wezterm/graphs/contributors">
<img src="https://contrib.rocks/image?repo=biscuit-colorscheme/wezterm" />
</a>

<p align="center">
  <img src="https://raw.githubusercontent.com/Biscuit-Colorscheme/.github/main/assets/color-cycle-light.png" alt="Biscuit palette" width="400" />
</p>


