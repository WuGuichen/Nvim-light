# Nvim-light\n
" xmodmap -e 'clear Lock' -e 'keycode 0x42 = Escape'
let mapleader=" "
syntax on
 
set number
set relativenumber
set nocursorline  
set wrap   " huanhang
set showcmd
set wildmenu
set hlsearch
exec "nohlsearch"
set incsearch    
set ignorecase
set smartcase 

noremap <LEADER><CR> :nohlsearch<CR>    
    
map S :w<CR>    
map s <nop>    
map sq :q<CR>    
map R :source $MYVIMRC<CR>
