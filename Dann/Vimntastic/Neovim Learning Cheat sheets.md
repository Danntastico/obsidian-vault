***Side Note: keep in mind that `<leader>` key means a key you've mapped, in my case was: space ` `***
### Plugins enabled: 
#### `Undotree`
Undo history visualizer, [more info here](https://github.com/mbbill/undotree) 
`<leader> u`: Will show History window. 

#### `Harpoon
Switch between files by mapping some keys, [more info here](https://github.com/ThePrimeagen/harpoon)
`<leader>a`: Add a file to the list
`Ctrl + e`: Toggle Quick menu 
`Ctrl + l`: Quick opens first file in list 
`Ctrl + t`: Quick opens second file in list
`Ctrl + n`: Quick opens third file in list 
`Ctrl + s`: Quick opens fourth file in list 

#### `Telescope`
_Need installing dependencies, use `checkhealth telescope` command to check if it is correctly installed._  
A Fuzzy finder. Very useful for finding files and do Searches in those files. [more info here](https://github.com/nvim-telescope/telescope.nvim)

`<leader> pf` for finding files 
`Ctrl + p` for finding git files 
`<leader> ps`for performing a `grep` search
`<leader>vh` open help tags popup

#### `Fugitive`
Git plugin for Vim, this is an extensive and very useful one, [more info here](https://github.com/tpope/vim-fugitive)
`<leader>gs` Open Git 
`<leader>p` perform a `git push`
`<leader>P` perform a `git pull --rebase`
`<leader>t` perform a `git push -u origin `

You can perform other commands directly for the command prompt in _Execute mode_ (`:`) 
- `: Git add`
- `: Git status`
get a full list of commands with `:help fugitive`

#### `LSP-Zero` 
Plugin for getting a bundle of other plugins for autocompletion and a full language server (Mason) installation right inside Neovim.
- Use `Mason` to get a full list of language servers available for install, navigate to the plugin you want and hit `i` for installing it. 
- use `gd` to go to the reference you need 
- use `<leader>vrr` to see a full list of references of a value 
- use `<leader>vrn` to rename a reference 


