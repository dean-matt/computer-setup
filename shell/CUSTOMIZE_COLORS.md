# Shell Coloring

## Terminal Colors

Terminal colors can be customized via the settings menu. I've made a profile and included it in this repo for easy import

## Syntax Highlighting

[Oh My ZSH](https://github.com/ohmyzsh/ohmyzsh) can be combined with (zsh-syntax-highlighting)[https://github.com/zsh-users/zsh-syntax-highlighting] by following these steps

1. Install Oh My ZSH by running:

   `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

2. Install zsh-syntax-highlighting in Oh My ZSH's plugins folder by running:

   `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`

3. Adding `zsh-syntax-highlighting` to the `plugins` variable in `.zshrc`, similar to the following:

   `plugins=(git zsh-syntax-highlighting)`

> I found that using hex color codes was not working and ended up using [xterm-256](https://github.com/gawin/bash-colors-256) color codes
