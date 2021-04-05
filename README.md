# TMUX configuration

### How to install 'tmux'

Please check the official website https://github.com/tmux/tmux/wiki/Installing

### Where to clone this project

- If you are using 'MacOS' or 'Linux', Please use the following command

  ```zsh
  git clone https://github.com/kafelix496/tmux.git ~/.config/tmux/
  ```

  :pushpin:**After you clone it, you need to make a symbolic link**

  ```zsh
  ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf
  ```

- If you are using 'Windows', **Please change your computer**. :zipper_mouth_face: ( I'm sorry but I don't know about 'Windows' )

### Dependencies

- tmux tpm

  ```zsh
  git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/tpm/
  ```

### Installing plugins

When you open tmux, you need to execute `Prefix` + <kbd>I</kbd>

### Custom key bindings

- `Prefix` : Ctrl + b
- `Prefix` + <kbd>|</kbd> : Split window vertical
- `Prefix` + <kbd>\_</kbd> : Split window horizontal
- `Prefix` + <kbd>j</kbd> : Focus to bottom pane
- `Prefix` + <kbd>k</kbd> : Focus to top pane
- `Prefix` + <kbd>h</kbd> : Focus to left pane
- `Prefix` + <kbd>l</kbd> : Focus to right pane
- `Prefix` + <kbd>r</kbd> : Rename window name
- `Prefix` + <kbd>R</kbd> : Rename session name
