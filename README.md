dotfiles
========

*A set of vim, zsh, git, and tmux configuration files.*

Use in combination with [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles).

## Usage

```
git clone https://github.com/thoughtbot/dotfiles.git .dotfiles
git clone https://github.com/arnewauters/dotfiles.git .dotfiles-local
env RCRC=$HOME/.dotfiles-local/rcrc rcup
```

```
ln -s $HOME/.vim $HOME/.nvim
ln -s $HOME/.dotfiles/vimrc $HOME/.nvimrc
```
