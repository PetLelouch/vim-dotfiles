# VIM

**First of all**
- Install nodejs
- Install ripgrep (install from winget)
- Download nerd font form official site, install and set in parameters of powershell, then in ~\vimfiles\plugged\vim-devicons\plugin\webdevicons.vim set css icon on cs icon in dictionary (just copy)

**Install vim-plug**
Install vim-plug from github. In powershell: iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`ni $HOME/vimfiles/autoload/plug.vim -Force`

**After PlugInstall**
- Run :let g:coc_node_path = "C:\\Program Files\\nodejs\\node.exe" for set node path for coc
- Open .cs file for install omnisharp lsp

**For JS**
- Run :CocInstall coc-tsserver coc-json

