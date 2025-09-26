## Keymaps

Below is a list of keymaps useful for coding, categorized by functionality. `<leader>` is Space.

### General Editing and Navigation
- `<leader>pv`: Open file explorer.
- `J` (visual): Move lines down.
- `K` (visual): Move lines up.
- `J`: Join lines.
- `<C-d>`: Scroll down, center.
- `<C-u>`: Scroll up, center.
- `n`: Next search, center.
- `N`: Previous search, center.
- `=ap`: Format paragraph.
- `<leader>p` (visual): Paste without yanking.
- `<leader>y` (normal/visual): Yank to clipboard.
- `<leader>Y`: Yank line to clipboard.
- `<leader>d` (normal/visual): Delete without yanking.
- `<C-c>` (insert): Exit insert mode.
- `<leader>s`: Replace word under cursor.
- `<leader>x`: Make file executable.
- `<leader>ee`: Insert Go error block.
- `<leader>ea`: Insert Go assertion.
- `<leader>ef`: Insert Go fatal log.
- `<leader>el`: Insert Go logger error.
- `<leader><leader>`: Source file.

### LSP and Diagnostics
- `gd`: Go to definition.
- `K`: Hover.
- `<leader>vws`: Workspace symbols.
- `<leader>vd`: Diagnostic float.
- `<leader>vca`: Code action.
- `<leader>vrr`: References.
- `<leader>vrn`: Rename.
- `<C-h>` (insert): Signature help.
- `[d`: Next diagnostic.
- `]d`: Previous diagnostic.
- `<leader>zig`: Restart LSP.

### Telescope
- `<C-p>`: Git files.
- `<leader>pf`: Find files.
- `<leader>ps`: Grep string.
- `<leader>pS`: Grep word.

### Testing (Neotest)
- `<leader>tt`: Nearest test.
- `<leader>tT`: File tests.
- `<leader>ta`: All tests.
- `<leader>tl`: Last test.
- `<leader>ts`: Toggle summary.
- `<leader>to`: Open output.
- `<leader>tS`: Stop tests.

### Formatting
- `<leader>f`: Format buffer.

### Git and Diagnostics (Fugitive/Trouble)
- `<leader>gs`: Git status.
- `<leader>nt`: Toggle Trouble.
- `<leader>n]`: Next Trouble.
- `<leader>n[`: Previous Trouble.

### Debugging (DAP)
- `<leader>db`: Toggle breakpoint.
- `<leader>dB`: Conditional breakpoint.
- `<leader>dc`: Continue.
- `<leader>dC`: Run to cursor.
- `<leader>dg`: Go to line.
- `<leader>di`: Step into.
- `<leader>dj`: Step over.
- `<leader>dk`: Step out.
- `<leader>dl`: Run last.
- `<leader>dr`: Toggle REPL.
- `<leader>dS`: Show scopes.
- `<leader>dt`: Terminate.
- `<leader>du`: Toggle UI.
- `<leader>dp`: Pause.
- `<leader>dP`: Pause thread.
- `<leader>dh`: Hover.
- `<leader>d?`: Preview.
- `<leader>td`: Debug test.

### Undo
- `<leader>u`: Toggle Undotree.

### Miscellaneous
- `<leader>tf`: Plenary test.
- `<C-f>`: Tmux sessionizer.
- `<M-h>`: Sessionizer vertical.
- `<M-H>`: Sessionizer new window.
- `<C-k>`: Next quickfix.
- `<C-j>`: Previous quickfix.
- `<leader>k`: Next loclist.
- `<leader>j`: Previous loclist.
- `<leader>mr`: Cellular automaton.

- **Other Dependencies**: Ensure ripgrep is installed for Telescope grep. Run `:Lazy sync` to manage plugins.

Run `:checkhealth` for config diagnostics.


