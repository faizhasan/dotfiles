# Dot Files Repo

**Run sheet**
1. Install [Homebrew](https://brew.sh)
1. Install [Prezto](https://github.com/sorin-ionescu/prezto)
1. Install [iTerm](https://www.iterm2.com/downloads.html)
1. Run `brew bundle` from the root of this repo
1. Run `bootstrap.sh` from the root of this repo
1. Install fonts in `iterm` directory
1. Make **iTerm** the default shell (from menu)
1. Install **iTerm** [shell integration](https://www.iterm2.com/shell_integration.html) (from menu)
1. Update **iTerm** to [load preferences from file](http://stratus3d.com/blog/2015/02/28/sync-iterm2-profile-with-dotfiles-repository/)
1. Restart **iTerm** and make sure Base 16 Tomorrow profile is selected
1. Set up **Vim** with:
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim +PluginInstall +qall
```
