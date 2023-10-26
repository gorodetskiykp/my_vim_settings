# my_vim_settings
Настройки vim

- место: ~/.vimrc

## Plugins
### Установка Plug
- curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
call plug#begin('~/.vim/plugged')
    Plug 'leafgarland/typescript-vim'
call plug#end()
:source %
:PlugInstall
### Списки
- https://github.com/jiangmiao/auto-pairs
- https://github.com/leafgarland/typescript-vim
- https://github.com/drewtempelmeyer/palenight.vim
