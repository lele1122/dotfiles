#Vim Configurations#


##Usage##


### Mac and Linux ###

	shell
	cd ~
	ln -s $DOTFILES_HOME/vim_config/vimrc .vimrc
	ln -s $DOTFILES_HOME/vim_config/vim .vim


### Windows ###

	batch
	cd %VIM_PROGRAM_PATH%
	mklink /d vimfiles %DOTFILES_HOME%\vim
	mklink _vimrc vimfiles\vimrc