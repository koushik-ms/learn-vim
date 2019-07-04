# List of programming features

Of course with Vim you get most of syntax Highlighting for free. Here I list the commonly used programmer features.

:set nu - turn on line-numbers. Very useful for all other commands accept line-numbers
:u - undo (The most important programmer feature)
.  - Redo (very smart redo)

## Copy-paste

You can use `y` to copy (yank) and `d` to cut in command mode.

  3dd - cut three lines
  3yy - cut 3 lines
  :3, 15y - Copy from line 3 to 15 (both inclusive)
  :3, 15d - Cut from line 3 to 15 (both inclusive)
  mk  - mark with alphabet k (use mark 'k')
  y'k - copy (yank) from mark till point
  d'k - cut (delete) from mark till point

## Move by blocks
  %   - Jump to matching paren
  mb  - Mark with 'b'
  mb% - select block (mark and then jump to end)
  zf'b- fold selected (from point to mark)

## Auto-completion by default Enabled!
  Use C-n to show completions!
  
## Multiple file edits
  :Explore - open file-explorer (use arrow/ navigation keys to move about and Enter to open)
  vim -p <file1> ... - open multile files as tabs

