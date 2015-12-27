# vim
# THIS ONE IS FORKED FROM https://github.com/morphoen/vim


How to Install:
1. install tools
  sudo apt-get install ctags cscope git
2.remove the orignal vim configuration
  mv ~/.vim ~/.vim.orig
  mv ~/.vimrc ~/.vimrc.orig
3.clone from git
  git clone https://github.com/morphoen/vim.git ~/.vim
4.link the vimrc config file
  ln -s ~/.vim/vimrc ~/.vimrc

5.clone the essensial vim plugins 
  git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
  
6.Install the plugins
  run command ":BundleInstall" in vim.
