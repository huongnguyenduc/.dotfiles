# .dotfiles

## Create symlinks in the Home directory to the real files in the repo

`ln -s ~/.dotfiles/.zshrc ~/.zshrc`

`ln -s ~/.dotfiles/.gitconfig ~/.gitconfig`

## Install Homebrew

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

## Pass in the Brewfile location...

`brew bundle --file ~/.dotfiles/Brewfile`

## ...or move to the directory first

`cd ~/.dotfiles && brew bundle`
