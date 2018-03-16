# Boot2env

> Just a toolkit I wrote to help my dev.

> Contain 2 command: ```coder and bootvm```

[![Build Status](https://travis-ci.org/springhack/boot2env.svg?branch=master)](https://travis-ci.org/springhack/boot2env) [![NPM version](https://img.shields.io/badge/boot2env-flat-green.svg)](https://www.npmjs.com/package/boot2env)

### Command ```bootvm```:

> A command to connect to VirtualBox or remote SSH host.

> Local SSH config hard code to bootvm, change it by yourself

###### ~/.ssh/auto_login

> is config file for bootvm, only if it exists this command can be run. file format like this:

```
hostname                username        password    port    AuthKeyFilePath
115.159.152.88          ubuntu          *           22      ~/Documents/Keys/Alxw
```

> this command try to connect via password default, place ```*``` to use AuthKeyFile

### Command ```coder```: 

> A command to cerate project, react component or config files.

> You can run ```coder -h``` to see help

### Config files:

> Need some dependencies, you can run this to get all (I think you use macOS):

> For YouCompleteMe, just run `./install.py --clang-completer --system-libclang`

```
# For powerline
pip3 install powerline-status
# For powerline fonts
git clone https://github.com/powerline/fonts.git
cd fonts
./install.sh
# For python
brew install python
# For cmake
brew install cmake
# For ctags
brew install ctags
# For tmux
brew install tmux
# For ack.vim
brew install the_silver_searcher
# For jsctags
npm install -g git+https://github.com/ramitos/jsctags.git
# For bash_completion
brew install bash-completion
# For reattach-to-user-namespace
brew install reattach-to-user-namespace
# For tpm
mkdir -p ~/.tmux && git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
# For vundle
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
# For vim colorscheme
mkdir -p ~/.vim/colors && curl https://raw.githubusercontent.com/cnj4/horseradish256/master/colors/horseradish256.vim -o ~/.vim/colors/horseradish256.vim
```

### Updates:

> Add tmux plugins manager

> Update vimrc & tmux

> Update vimrc

> Update webpack and plugins, coloscheme

> Update vimrc colorscheme

> Update vimrc with jsctags support

> Change babel-preset-latest to babel-preset-env

> Add loading 
