# operators:
---

## Definition:
```
 determines which action you want to perform: deleting, changing, yanking, formatting, etc.
```

## Example:

```
    d corresponds to the delete operator. Since d is an operator, you can follow the {operator}{count}{motion} formula and combine it with all the motions you’ve learned thus far:

    c (change): Change deletes a piece of text and then sends you into Insert mode so that you can continue typing, changing the original text into something else. The change operator is like the d and i commands combined into onetwo. This duality makes it the most useful operator
    y (yank): Copy in Vim jargon
    p (put): Paste in Vim jargon
    g~ (switch case): Changes letters from lowercase to uppercase and back. Alternatively, use gu to make something lowercase and gU to make something uppercase
    > (shift right): Adds indentation
    < (shift left): Removes indentation
    = (format code): Formats code
```

- Double an operator to make it operate on a whole line: dd deletes a whole line, cc changes a whole line, etc.

- Capitalize an operator to have it perform a stronger (or alternate) version of its default behavior: D deletes from the cursor to the end of the line, C changes to the end of a line, Y like yy copies a complete line, P pastes something before the cursor, etc.

### Related: