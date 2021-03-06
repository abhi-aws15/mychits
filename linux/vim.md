# Vim CLI Basics

## Related tutorial
- https://laracasts.com/series/vim-mastery

## Cheatsheet
- https://vim.rtorr.com/

## Config
Custom config: `~/.vimrc`

## Colorschemes
- https://github.com/rakr/vim-one

## Commands 

### Navigation

Insert mode: `i`

Command mode: `ESC`

Navigation: `h`, `j`, `k`, `l`

Move to next word: `w` (combine with number to skip words)

Move to beginning of word: `b` (combine with number to skip words)

Move to end of word: `e` (combine with number to skip words)

Insert three dashes: `3i-`

Jump to next dash: `f-`

Jump to third dash: `3f-`

Jump to next bracket: `%`

Jump to beginning of line: `0`

Jump to end of line: `$`

Jump to next occurence of a word: `*`

Jump to previous occurence of a word: `#`

Jump to beginning of the file: `gg`

Jump to end of the file: `G`

Browser current working directory: `:e .`
(allows browsing and searching with `/`)

Search word: `/` (Use `n` and `N` to navigate)

Insert as new line: `o` and `O`

Cut chars: `x` and `X`

Replace char: `r`

Delete: `d`

Cut whole line: `dd`

Cut text e.g. next word: `dw`

Undo: `u`

Redo: `ctrl + r`

Repeat last command: `.`

Switch to visual mode: `v` and `V` (select entire line)

Copy selected: `y`

Copy entire line: `yy`

Paste: `p`

Save changes: `:w`

Quit Vim: `:q`

Quit without saving: `:q!`

Save and exit: `ESC` + `:x`

Force quit (without saving): `ESC` + `:q!`

Source current file: `:so %`

Compare two files: `vim -d index1.php index2.php`

### Split view

Horizontal split: `:sp`

Vertical split: `:vsp`

Jump up: `ctrl + k`

Jump down: `ctrl + j`

Jump left: `ctrl + h`

Jump right: `ctrl + l`


## Apps

### MacVim

Open app: `mvim`


## Plugins


### Vundle

Download: https://github.com/VundleVim/Vundle.vim

Command: `:PluginInstall`


### Vinegar

Browser current working directory: `-`

Go up one folder: `-`

Create directory: `d`

Delete directory: `D` (asks for confirmation)

Delete selected file: `D` (asks for confirmation)

Create file: `%`


### NERDTree

Toggle sidebar: `:NERDTreeToggle`


### CtrlP

Switch from file to file: `ctrl + p`