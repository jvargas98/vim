# Vim commands

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
