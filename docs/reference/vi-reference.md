# Vi/Vim Cheatsheet

## Modes
- **Command Mode**: Default mode for navigation and editing commands.
- **Insert Mode**: Enter text (`i` to enter, `Esc` to exit).
- **Visual Mode**: Select text (`v` for character, `V` for line, `Ctrl+v` for block).

---

## File Operations
- `:w` - Save file.
- `:wq` or `ZZ` - Save and quit.
- `:q` - Quit (fails if unsaved changes).
- `:q!` - Quit without saving.
- `:w filename` - Save as a new file.
- `:e filename` - Open a file.
- `:r filename` - Insert content from another file.

---

## Insert Mode Commands
- `i` - Insert before the cursor.
- `I` - Insert at the beginning of the line.
- `a` - Append after the cursor.
- `A` - Append at the end of the line.
- `o` - Open a new line below.
- `O` - Open a new line above.

---

## Navigation
- `h` - Move left.
- `l` - Move right.
- `j` - Move down.
- `k` - Move up.
- `0` - Move to the start of the line.
- `^` - Move to the first non-blank character of the line.
- `$` - Move to the end of the line.
- `w` - Jump to the start of the next word.
- `e` - Jump to the end of the current/next word.
- `b` - Jump to the beginning of the previous word.
- `G` - Go to the last line.
- `gg` - Go to the first line.
- `:n` - Go to line `n`.

---

## Editing
- `x` - Delete the character under the cursor.
- `X` - Delete the character before the cursor.
- `dd` - Delete the current line.
- `yy` - Copy (yank) the current line.
- `p` - Paste after the cursor.
- `P` - Paste before the cursor.
- `u` - Undo last change.
- `Ctrl+r` - Redo undone change.
- `r` - Replace the character under the cursor.
- `R` - Replace text (overwrite mode).

---

## Visual Mode
- `v` - Start character-wise selection.
- `V` - Start line-wise selection.
- `Ctrl+v` - Start block selection.
- `d` - Delete selected text.
- `y` - Yank (copy) selected text.
- `>` - Indent selected text.
- `<` - Un-indent selected text.

---

## Search and Replace
- `/pattern` - Search forward for "pattern".
- `?pattern` - Search backward for "pattern".
- `n` - Repeat the search forward.
- `N` - Repeat the search backward.
- `:%s/old/new/g` - Replace "old" with "new" globally in the file.
- `:n,m s/old/new/g` - Replace "old" with "new" in lines `n` to `m`.

---

## Miscellaneous
- `.` - Repeat the last command.
- `Ctrl+g` - Show current file name and position.
- `:set nu` - Show line numbers.
- `:set nonu` - Hide line numbers.
- `:!command` - Run a shell command.
- `:help` - Open help documentation.

---

## Exit Modes
- `:wq` - Save and quit.
- `:q!` - Quit without saving.
- `ZZ` - Save and quit.

---

Use this cheatsheet as a quick reference to master Vi/Vim!
