# How it Looks

![Screenshot](http://is.gd/XzLpF9)

# Installation Instructions

    git clone https://github.com/kuroir/dotfiles ~/dotfiles/
    cd ~/dotfiles/
    git submodule init
    git submodule update
    ln -s ~/dotfiles/.ackrc ~/.ackrc
    ln -s ~/dotfiles/.vimrc ~/.vimrc
    ln -s ~/dotfiles/.tmux.conf ~/.tmux.conf

# Adding More Bundles

    git submodule add https://github.com/someone/something.vim.git .vim/bundle/helpers/something

