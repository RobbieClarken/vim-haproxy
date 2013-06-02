## About

[Vundle](https://github.com/gmarik/vundle) compatible [haproxy.vim](http://haproxy.1wt.eu/download/contrib/haproxy.vim).

## Usage

1. Install [Vundle](https://github.com/gmarik/vundle).
2. Add the following to your `.vimrc` file:

  ```vim
  Bundle 'RobbieClarken/vim-haproxy'
  autocmd BufRead,BufNewFile haproxy* set ft=haproxy
  ```
  
3. Run `vim +BundleInstall +qall`.
