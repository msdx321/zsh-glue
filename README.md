# fzf-glue

A **Zsh** function to fuzzy-search command history with [fzf](https://github.com/junegunn/fzf). It removes the history line numbers (e.g. `37 reload`) so only the command (`reload`) is inserted.

## Installation
1. Install **fzf** (via `brew`, `apt`, etc.).
2. Copy this script into `~/.zshrc` (or source it from there).
3. Restart your shell or run `source ~/.zshrc`.

## Usage
- Press Ctrl+G to open the history search.
- Select a command; line numbers are stripped automatically.
