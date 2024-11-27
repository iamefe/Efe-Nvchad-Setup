# Notes

## For new Nvchad installation
Install Neovim this from https://github.com/neovim/neovim

Then install NvChad this way. 
```bash
git clone https://github.com/NvChad/starter ~/.config/nvim && nvim
```
After which you should follow the remaining instructions at
https://nvchad.com/docs/quickstart/install

Then carefully assess the files in this dotfiles repo for any version/compatibility changes with your new NvChad installation before pasting each one's content accordingly.

## Set aliases in .bashrc or .zshrc
alias vim='clear && nvim'
alias nvim='~/nvim-linux64/bin/nvim'


## POPULAR SHORTCUTS AS SEEN IN VS CODE
- Go to import definition - gd
- Move line up or down - alt + k or j
- Duplicate line down - Leader d (n mode)
- Undo and redo - u and ^R
- Toggle comment - Leader /
- Horizontal terminal - Leader h (q to quit) Avoid using this terminal style. Use an actual terminal tab.
- Toggle NVIM Tree - C-N
- Change NVIM Tree directory - ; the cd <directory name> ENTER
- Shortcut cheatsheet - Leader ch
- Toggle relative numbers - Leader rn
- Toggle line numbers - Leader n
- Floating file browser with the current path - sf (normal mode)
- Find in current buffer - Leader fz (this uses Telescope).
- Super powers - :Telescope
- Using Telescope to see all keymaps - Leader km or :Telescope keymaps
- Lazy - Leader l
- Quit - Leader q
- Close Nvim - Leader Q
- Close tab (buffer) - Leader X
- IN YOUR FILE BROWSER
        - h to go to the parent directory (like going cd ../)
        - c to create a new file
        - r to rename a file
        - s to select a file and m to move it
        - s to select a file and d to delete it with confirmation
- Indent multiple lines in visual mode: `>` or `<`
- Select matching tag: `%`
