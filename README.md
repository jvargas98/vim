# Vim commands

## Basic

- `:w` - Save document.
- `:q` - Quit document.
- `:q!` - Quit document without saving.
- `:help` - Show commands.
- `u` - Undo a change.
- `Ctrl + R` - Redo a change.

## Modes

- ### Insert mode
    `i` - *Enter to insert mode.*
- ### Normal mode
    `Esc` - *Enter to normal mode.*

## Basic movements

- `h` - Move to the left.
- `l` - Move to the right.
- `k` - Move to the up.
- `j` - Move to the down.
- `0` - Move to the start of line.
- `$` - Move to the end of line.
- `gg` - Move to the beginning of the file.
- `G` - Move to the end of the file.
- `3G` - Move to the line 3.
## Word movements

- `b` - Move to the beginning of the word.
- `w` - Move to the start of the next word.
- `e` - Move to the end of the word.

## Number powered movements

- `5w` - Move to the next five words, the same as pressing `w` five times.
- `5l` - Move to the next five characteres.

## Insert text repeatedly

- `3iHello + Esc` - Insert the word 'Hello' three times.

## Search methods
- `f + character` - Find the next character selected. `fa` find next 'a'.
- `Number + f + character` - Find the occurrence number of character. `3fa` find the 3rd occurrence of 'a'.
- `*` - Find the next occurrence of the word under cursor.
- `#` - Find the previous occurrence of the word under cursor.
- `/ + text or regexps` - Find the subsequent matches. `/text` search the word 'text'.
- `n` - Repeat the search for next occurrence.
- `N` - Repeat the search for previous occurrence.

## Manipulate text

- `o` - Insert text into a new line.
- `O` - Insert new line above the current line.
- `x` - Romove the last character.
- `X` - Remove the previous character.
- `r` - Replace character under cursor.
- `dw` - Delete the first word after cursor.
- `db` - Delete the first word before cursor.
- `d + number + e` - Delete the next number of words.
