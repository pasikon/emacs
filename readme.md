# my emacs config

Cheatsheet

![Emacs + Tmux](/emacs+tmux.png?raw=true "Emacs + Tmux")

## keys
Key | Desc
--- | ---
`M` | alt
`C` | control
`S` | shift
`s` | super
`ESC` | escape
`RET` | enter

## help
Key | Desc
--- | ---
`C-h i` | open manual
`C-h m` | describe mode
`C-h f` | describe function
`C-h k` | describe key

## navigation
Key | Desc
--- | ---
`M-m` | move point to the first non-whitespace character on this line
`C-M-f` | move forward by s-expression
`C-M-b` | move backward by s-expression

## bookmarks
Key | Desc
--- | ---
`C-x r m` | set
`C-x r l` | list
`C-x r b` | jump

## evil
Key | Desc
--- | ---
`fd` | escape vi mode
`i` | insert text before cursor
`A` | append text at the end of the line
`o` | begin a new line below the cursor and insert text
`u` | undo
`x` | delete character after the cursor
`dd` | delete line
`daw` | delete a word
`D` | delete the characters under the cursor until the end of the line
`e` | forward to the end of word
`b` | backward to the end of word
`y` | copy marked text
`yy` | copy line
`p` | paste text after cursor
`P` | paste text before cursor
`/pattern` | search
`:%s/old/new/g` | replace old with new in all lines
`ESC C-SPC` | escape vi mode and set the mark at point
`ESC :29 RET` | escape vi mode and go to line 29

## emacs
Key | Desc
--- | ---
`C-x c` | exit
`C-g` | abort
`M-x` | command
`C-x f` | find a file
`C-x s` | save all file
`C-x 3` | split vertically
`C-x 2` | split horizontally
`C-x 0` | close buffer
`C-x o` | switch buffer
`C-x 1` | close all other buffers
`C-x b` | select another buffer
`C-x k` | kill a buffer
`C-x left` | previous buffer
`C-x right` | next buffer

## emacs plugins
Key | Desc
--- | ---
`M-f` | search for a file in a project
`M-F` | grep in a project
`TAB` | autocomplete
`M-/` | undo tree
`M-1` | switch to window 1
`M-N` | switch to window N

## neotree
Key | Desc
--- | ---
`C-c n` | toggle neotree
`A` | max/min neotree
`H` | toggle display hidden files
`C-c C-n` | create a file or directory
`C-c C-d` | delete a file or directory
`C-c C-r` | rename a file or directory
`g` | refresh

## elscreen
Key | Desc
--- | ---
`C-z c` | create screen
`C-z k` | kill screen
`gt` | next screen
`gT` | previous screen

## ensime
Key | Desc
--- | ---
`M-RET` | jump to the definition
`M-,` | pop back to the previous position
`C-c C-v r` | list all references to the symbol
`C-c C-v t` | show the type of the symbol
`C-c C-r a` | add type to the symbol
`C-c C-r o` | organize imports in the current file
`C-c C-r t` | import the type
`C-c C-r r` | rename the symbol
`TAB` | autocomplete

## org-mode
Key | Desc
--- | ---
`C-c a a` | show agenda
`C-c a t` | global todo list
`C-c C-s` | schedule a task
`C-c C-t` | mark task as done
`S-TAB` | toggle overview
