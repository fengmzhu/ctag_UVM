#how to generate tags
ln -s ./ctags ~/.ctags
cd <dir with src code>
ctags -R .

#UVM 1.2 source code and ctag
move t
add the following line in your .vimrc

set tags=~/ctag_UVM/tags
or
set tags+=~/ctag_UVM/tags

