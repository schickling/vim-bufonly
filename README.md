vim-bufonly
===========

Delete all the buffers except the current buffer.


## Usage

`:BufOnly` without an argument will delete all buffers but the current one.  
`:BufOnly myBuffer` with an argument will close all buffers but the supplied buffer name/number.

Aliases: `:Bonly`, `:BOnly`, `:Bufonly`

## Installation

This plugin follows the standard runtime path structure, and as such it can be installed with a variety of plugin managers:

*  Pathogen
  *  `git clone https://github.com/schickling/vim-bufonly ~/.vim/bundle/vim-bufonly`
*  NeoBundle
  *  `NeoBundle 'schickling/vim-bufonly'`
*  Vundle
  *  `Bundle 'schickling/vim-bufonly'`
*  VAM
  *  `call vam#ActivateAddons([ 'vim-bufonly' ])`
*  manual
  *  copy all of the files into your `~/.vim` directory


## Credits
This plugin is based on [Christian J. Robinson's script](http://www.vim.org/scripts/script.php?script_id=1071).
