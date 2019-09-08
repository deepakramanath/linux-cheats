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
`[0-9]dd` | Delets the total number of lines. `3dd` delets 3 lines from curson 
`dw` | Delets one word from the current position to the begining of next word
`d$` | Delets from current cursor to end of current line
`d0` | Delets from current curson to beginning of current line
`dG` | Delets everything from curson to end of file (EOL)
`d[0-9]G` | Delets from current line to number. `d15G` delets from curson to 15 line




 


