# keyboard-mappings
Custom keymappings for MacOS, mostly for typing Hungarian characters using QWERTY in vim.

Made using [ukelele](https://software.sil.org/ukelele/)

## Included keymappings:

#### tilde
I type in both English and Hungarian. I prefer to use the same QWERTY layout for both (I can never remember the Hungarian layout). MacOS offers a nice long-press functionality to access diacritical marks (ó, ö, ő, ú, ü, í, é, á).
Unfortunately, long-press does not work in vim/neovim. Hence this keymap. The tilde key becomes a mode selector to enter diacritical mode. In that mode: 
- a -> á
- e -> é
- i -> í
- o -> ó, p -> ö, [ -> ő (note that these are consecutive keys)
- u -> ú, j -> ü (note that j is below u)
- Typing ` twice yields an actual tilde

Shift is respected to give the capital of each character.
