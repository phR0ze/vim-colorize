# vim-colorize
Adds color to a couple vim plugins that I use

## nerdtree
The first plugin was nerdtree and provides some great file picking type capabilities as a slide out 
navigation panel. I wanted to be able to add some custom color to match my perferred color scheme 
`deus`.

## vim-devicons
The second is `vim-devicons`, which  is an excellent vim plugin for adding icons to various plugins
I wanted to be able to set specific colors for groups of icons.

### Manually adding colors without this plugin
Drop the following in your ***~/.vimrc***
```bash
let g:ColorizeDevicons_map = {
  \'grey': ['CECECE', ['▸', '▾','']],
  \'tan': ['C09553', ['','','','']],
  \'cyan': ['4DFFFF', ['','']],
  \'blue': ['689FB6', ['','','','','','','','','','','','']],
  \'darkBlue': ['44788E', ['','']],
  \'purple': ['834F79', ['','','','','','']],
  \'red': ['AE403F', ['','','','','','']],
  \'gold': ['F5C06F', ['','','']],
  \'yellow': ['F5DE19', ['','','','λ','','']],
  \'orange': ['D4843E', ['']],
  \'darkOrange': ['F16529', ['','','','','']],
  \'pink': ['CD6799', ['','','']],
  \'green': ['8FAA54', ['','','','','','']],
  \'white': ['FFFFFF', ['','','','']]
\}
```

## Credits
As part of this plugin I leveraged the hex to ctermfg conversion functions found in the colorscheme
***desert256.vim*** http://www.vim.org/scripts/script.php?script_id=1243
