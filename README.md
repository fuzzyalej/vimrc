
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    git clone https://github.com/fuzzyalej/vimrc.git
    mv vimrc/.vimrc ~/.vimrc
    rm -rf vimrc
    vim +BundleInstall +qall
