# vim-motions:

Definition:
 Word motions let you jump from word to word in either direction (from left to right or right to left). As such, they allow you to move faster than the basic horizontal motions h and l.


- Use b (back) to jump to the beginning of a word backwards
- Use e (end) to jump to the end of a word
- Use ge to jump to the end of a word backwards

To move extremely horizontally use:
- 0: Moves to the first character of a line
- ^: Moves to the first non-blank character of a line
- $: Moves to the end of a line
- g_: Moves to the non-blank character at the end of a line

To move extremely horizontally use:
- 0: Moves to the first character of a line
- ^: Moves to the first non-blank character of a line
- $: Moves to the end of a line
- g_: Moves to the non-blank character at the end of a line

To move vertically even faster when you have a target in mind, your best option is to search for that target with the /{pattern} and ?{pattern} commands:
- Use /{pattern} to search forward inside a file
- Use ?{pattern} to search backwards

Related:
