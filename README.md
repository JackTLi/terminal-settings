
## Installing vim
```bash
brew install vim --with-override-system-vi
```

## Cloning
``` bash
git clone https://github.com/JackTLi/terminal-settings.git ~/projects/terminal-settings
```

## Creating symlinks

  ```bash
  ln -s ~/projects/terminal-settings/.zshrc ~/.zshrc
  ln -s ~/projects/terminal-settings/.vimrc ~/.vimrc
  ```

## Potential issues:

> No module found named ycm_core
```bash
      cd ~/.vim/bundle/YouCompleteMe
      ./install.py --clang-completer
```

