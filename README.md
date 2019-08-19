* Config files and plugins for Neovim/Vim.
* Neovim stores by default files in the $HOME/.config/nvim
* init.vim is the ".vimrc" of nvim. Just change to ".vimrc" and move to $HOME to use it with Vim.
* init.vim saves the swap files to "$HOME/.cache/nvim/" make sure the folder exists.

* Neovim and Vim (version > 8) have native module support.
  - Neovim
    -> .local/share/nvim/site/*/pack/your_vim_plugin.vim
  - Vim
    -> .vim/pack/*/start/your_vim_plugin.vim
