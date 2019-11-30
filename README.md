# My dotfiles

Tested on Mac and Ubuntu.

## Install

1. Install vim, zsh, powerline fonts
2. Install Oh My ZSH
	- `git clone https://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh`
3. Install antigen
	- `curl -L git.io/antigen > antigen.zsh`
4. Install zsh plugins with antigen
	- `antigen`
5. Setup vundle
	- `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
	- `vim +PluginInstall +qall`
