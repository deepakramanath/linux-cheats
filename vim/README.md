VIM Cheat Sheet
===============

### Reference [The Linux Command Line - William Shotts](http://linuxcommand.org/tlcl.php)

Cursor movements
----------------
Key | Effect
----| ------
`0` | Beginning of the line
`$` |  End of the current line
`w` | Beginning of the next word or punctuation
`b` | Beginning of the previous word or punctuation
`[0-9]G` | To line nuber. `2G` for example moves to the second line
`G` | Moves to he last line of the file
`l` | Right one character
`h` | Left one character
`j` | One character down
`k` | One character up


Basic Editing
-------------

Key | Effect
----| ------
`a` | Insert mode at the cursor location.
`A` | Insert mode at the end of the line
`o` | Inserts new line below the current line
`O` | Inserts new line above the current line


Text Deletion Commands
----------------------

Key | Effect
----| ------
`x` | Delets current character
`[0-9]x` | Delets the total nmber of charactes. `3x` for example, delets 3 characters
`dd` | Delete current line
`[0-9]dd` | Delets the total number of lines. `3dd` delets 3 lines from cursor
`dw` | Delets one word from the current position to the begining of next word
`d$` | Delets from current cursor to end of current line
`d0` | Delets from current cursor to beginning of current line
`dG` | Delets everything from cursor to end of file (EOL)
`d[0-9]G` | Delets from current line to number. `d15G` delets from cursor to 15 line


Text Copying Commands
---------------------

Key | Effect
----| ------
`yy` | Copies current line
`[0-9]yy` |Copies the total number of lines. `3yy` copies 3 lines from cursor
`yw` | Copies one word from the current position to the begining of next word
`y$` | Copies from current cursor to end of current line
`y0` | Copies from current cursor to beginning of current line
`yG` | Copies everything from cursor to end of file (EOL)
`y[0-9]G` | Copies from current line to number. `y15G` copies from cursor to 15 line








 


