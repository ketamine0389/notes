# .vimrc Setup
### Setting up a `.vimrc` file
`.vimrc` is basically the config file for the Vim text editor. It may contain anything from basic config to installation of plugins.<br>
NOTE: This is set up for Linux subsystems, on Windows (using something similar to gVim, the file should be named `_vimrc`)

### Creation of `.vimrc`
In order to take effect, it should be created in the home directory, found with `$HOME/` [is that only on Debian-based distros?]  or `~/`<br>

```bash
touch ~/.vimrc
```

### Editing of `.vimrc`
Any text editor may be used to edit the file, as it is saved and treated as plain text. For this example I will be using Vim itself to edit the config.<br>

```bash
vi ~/.vimrc
```

Now that the file is open, **edits can be made such as the following**.<br>
For now, this will only contain my personal vimrc configs.<br>

```
"
" Colors
"
hi CursorLineNR cterm=bold ctermbg=239 ctermfg=yellow
hi CursorLine cterm=NONE ctermbg=239 ctermfg=NONE
hi LineNr ctermfg=59

"
" Settings / Preferences
"

" Enables auto detection for filetypes
filetype on

" Enables plugins automatically for the detected filetype
filetype plugin on

" Load correct indentation for detected filetype
filetype indent on

" Enable syntax highlighting
syntax on

" Enable line numbers
set number

" Highlight line the cursor is on
set cursorline

" Set tab width to 4 cols
set tabstop=4

" Use space chars instead of tab chars
set expandtab

" Highlight matching search chars
set incsearch

" Search by specific case
set smartcase

" Show the command last used
set showcmd

" Show matching words during a search
set showmatch

" Enable highlighting when searching
set hlsearch

" Increase command history (default 20)
set history=100

" Tab auto complete
set wildmenu

" Make it similar to bash auto complete
set wildmode=list:longest

" Disable editing of certain filetypes
set wildignore=*.docx,*.jpg,*.png,*.gif,*.pdf,*.exe,*.flv,*.img,*.xlsx

" Disable line wrapping
set nowrap

"
" Things to remember
"

" Disable backups
" set nobackup

" Highlight column the cursor is on (gross)
" set cursorcolumn
```

### Installing Plugins
More info here once I begin to install plugins.

