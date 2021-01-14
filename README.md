# Vim Instructions

* Copy .vimrc into working project. To make it work right away they remove
all plugins

* create undo directory in .vim because of this line set undodir=~/.vim/undodir

# Plugins
* First thing is to run vim-plug. Need to curl for it
> curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
>    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim 

We can use git hub links here to

YouCompleteMe is a special github plugin

To use completely we must download the languages we want it to work with
Review Documentation for YouCompleteMe below. (They have some outdated docs)
[YouCompleteMe](https://github.com/ycm-core/YouCompleteMe)

To do the above make sure you copy the .vimrc before running these next commands
Install python, cmake, build-essential
> sudo apt install build-essential cmake vim-nox python3-dev
Install mono, go, nodejs, jdk, npm
> sudo apt install mono-complete golang nodejs default-jdk npm

Go to where YouCompleteMe is
> cd ~/.vim/bundle/YouCompleteMe
Install YouCompleteMe
> python3 install.py --all
