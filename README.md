# Skylovescoffee's Tmux Config 

## Features ✨
- 🪶 Super lightweight. 
- 🧘 Minimalistic. 
- ⌨️ Native vim keybindings. 
- 📈 High resolution display. 
- 🔄 Simple and true to the original. (You shouldn't have any problems switching back to the original tmux.) 

## Requirements 🛠️
- Tmux. 📟
- Mac or Linux. (Untested on Windows, but WSL2 should work). 🐧
- [Tmux Plugin Manager (TPM)](https://github.com/tmux-plugins/tpm) 🧰
- A suitable terminal emulator. I like [Alacritty](https://github.com/alacritty/alacritty) 🚀

## Installation 🚀
- Make sure [Tmux Plugin Manager (TPM)](https://github.com/tmux-plugins/tpm) is installed.
- Copy the content from `tmux.conf` to either `$HOME/.tmux.conf` or `%XDG_CONFIG_HOME/tmux/tmux.conf`.
    - `%XDG_CONFIG_HOME/tmux/tmux.conf` is what I ***highly recommend.*** It should look something like `~/.config/tmux/tmux.config`.
    - `$HOME/.tmux.conf` is usually at `~/.tmux.conf`.
    - **If the directory does not exist, create it.** 📁
- Source the config with `tmux source ~/.config/tmux/tmux.conf`.
- Make sure you are in tmux and install the plugins with the keybinding `ctrl + b + I`.
    - (the i is capitalised so its more like `ctrl + b + shift + i`) 🛠️

Feel free to enjoy the enhanced tmux experience with this configuration! If you have any questions or feedback, don't hesitate to reach out. Happy Tmuxing! 🎉🐢
