# How it Looks

![Screenshot](https://dl.dropbox.com/u/4651065/screenshots/2012/11/22-18h40m56s.png)

# Installation Instructions

    git clone https://github.com/kuroir/dotfiles ~/dotfiles/
    cd ~/dotfiles/
    git submodule init
    git submodule update
    ln -s ~/dotfiles/.ackrc ~/.ackrc
    ln -s ~/dotfiles/.vimrc ~/.vimrc
    ln -s ~/dotfiles/.tmux.conf ~/.tmux.conf
    ln -s ~/dotfiles/.gitignore ~/.gitignore
    git config --global core.excludesfile

# Updating Modules

    git submodule foreach git pull origin master

# Make sure you're using vim that has Python

    In order to avoid errors, you should use brew installed vim.
    brew list
    brew install vim
      it might ask you to do
    brew install mercurial
      which is a dependency.


# Adding More Modules

    git submodule add https://github.com/someone/something.vim.git .vim/bundle/helpers/something

# Want to contribute?

Justs fork and do your thing. If you want me to merge into master, let me know.

If you want to have your own plugins that you don't think anyone else will want
place them inside `experimental` directory.

