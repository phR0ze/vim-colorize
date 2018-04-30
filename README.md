# vim-colorize
Adding color to various vim plugins

## vim-devicons
Excellent vim plugin for adding icons to various plugins

**Enable Colors for vim-devicons**  
Drop the following in your ***~/.vimrc***
```bash
let g:devicons_colormap = {
  \'lightgrey': ['CECECE', ['▸', '▾']],
  \'grey': ['999999', ['', '', '']],
  \'brown': ['905532', ['']],
  \'aqua': ['3AFFDB', ['']],
  \'blue': ['689FB6', ['','','','','','','','','','','']],
  \'darkBlue': ['44788E', ['','']],
  \'purple': ['834F79', ['','','','','','']],
  \'red': ['AE403F', ['','','','','','']],
  \'beige': ['F5C06F', ['','','','']],
  \'yellow': ['F09F17', ['','','λ','','']],
  \'orange': ['D4843E', ['']],
  \'darkOrange': ['F16529', ['','','','','']],
  \'pink': ['CB6F6F', ['','']],
  \'salmon': ['EE6E73', ['']],
  \'green': ['8FAA54', ['','','','','']],
  \'lightGreen': ['31B53E', ['','']],
  \'white': ['FFFFFF', ['','','','','']]
\}
```

## Credits
As part of this plugin I leveraged the hex to ctermfg conversion functions found in the colorscheme
***desert256.vim*** http://www.vim.org/scripts/script.php?script_id=1243
