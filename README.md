jsbeautify.vim
--------------

A plugin to format your javascript souce code

It can be helpful when reformatting JSON snippets and compressed javascript.


This fork of vim-scripts/jsbeautify has a couple small changes.


A js version can be found at:
[jsbeautifier.org](http://jsbeautifier.org/)


usage:
  <leader>ff
or
  bind the g:Jsbeautify() function to any short key you like

Changes:
- It is filetype plugin so it only loads for javascript files. This might not be ideal if you want to reformat .json files or use the javascript.jquery filetype.
- If you use JSLint's strict whitespace rules, then add "let g:Jsbeautify_jslint_whitespace = 1" to your .vimrc to use "function ()" instead of "function()"


Thanks to aj3423 fork creating the vimscript version of this brilliant reformatter.
