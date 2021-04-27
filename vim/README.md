My vim dotfiles.

# Setup

## For Mac

Use brew-packaged vim, not built-in MacVim.

```
brew install vim
brew unlink vim && brew link vim
exec -l $SHELL
```

## Common

Install [vim-plug][vim-plug] in an official manner, like

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

```
rm -f ~/.vimrc
ln -s ~/dotfiles/vim ~/.vim
chmod 755 ~/.vim && chmod 700 ~/.vim/trace
```





[vim-plug]:https://github.com/junegunn/vim-plug
