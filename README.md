# Setup

Clone the repo in your HOME path:

	git clone git://github.com/vieron/dotfiles.git ~/.dotfiles


Create symlinks:

	ln -s .dotfiles/zsh/zlogin .zlogin
	ln -s .dotfiles/zsh/zlogout .zlogout
	ln -s .dotfiles/zsh/prezto .zprezto
	ln -s .dotfiles/zsh/zpreztorc .zpreztorc
	ln -s .dotfiles/zsh/zprofile .zprofile
	ln -s .dotfiles/zsh/custom .zsh.custom
	ln -s .dotfiles/zsh/zshenv .zshenv
	ln -s .dotfiles/zsh/zshrc .zshrc


Fetch submodules:

	cd ~/.dotfiles
	git submodule update --init --recursive


Add a new completion:

	cd ~/.zsh.custom/completions
	ln -s /usr/local/share/zsh/site-functions/_wadus _wadus