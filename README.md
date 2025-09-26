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

### Change Log
* [33eee9ad](https://github.com/ahad/init.lua/commit/33eee9ad0c035a92137d99dae06a2396be4c892e) initial commits
* [cb210006](https://github.com/ahad/init.lua/commit/cb210006356b4b613b71c345cb2b02eefa961fc0) netrw, autogroups for yank highlighting, and auto remove whitespace
* [c8c0bf4a](https://github.com/ahad/init.lua/commit/c8c0bf4aeacd0bd77136d9c5ee490680515a106b) zenmode.  i really like this plugin
* [81c770d2](https://github.com/ahad/init.lua/commit/81c770d2d2e32e59916b39c7f5babbc8560f7a82) copilot testing
* [4a96e645](https://github.com/ahad/init.lua/commit/4a96e6457b0a0241ca7361ce62177aa6b9a33a38) fugitive mappings for push and pull
* [a3bad06a](https://github.com/ahad/init.lua/commit/a3bad06a4681c322538d609aa1c0bd18880f77c6) disabled eslint.  driving me crazy

## Local Setup

This config is based on ahad's, with local modifications:

- **Plugins**: Custom local plugins (e.g., harpoon, vim-with-me) were commented out in `lua/ahad/lazy/local.lua` to avoid "not installed" errors, as their directories don't exist locally. For public plugins, update to GitHub sources if needed (e.g., "ahad/harpoon").

- **Go and gopls**: Install Go via Homebrew (`brew install go`), then use `:MasonInstall gopls` for LSP support in Go files.

- **Other Dependencies**: Ensure ripgrep is installed for Telescope grep. Run `:Lazy sync` to manage plugins.

Run `:checkhealth` for config diagnostics.


