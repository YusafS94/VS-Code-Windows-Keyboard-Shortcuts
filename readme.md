# VS Code Windows shortcuts

Copied from [VS Code keyboard shortcuts PDF](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf) and converted into markdown. I prefer to have a markdown file over looking at a PDF for this kind of info, and there didnt seem to be any versions on github that were styled into tables properly so i thought i'd create one. I have included a separate markdown file with just the shortcuts, but I will include them here too for ease of use. Feel free to fork or git clone for your own purposes.

## General

| <div style="width:200px">Keys</div> | <div style="width:400px">Shortcut</div> |
| :---------------------------------- | :-------------------------------------- |
| `Ctrl+Shift+P, F1  `                | Show Command Palette                    |
| `Ctrl+P            `                | Quick Open, Go to File…                 |
| `Ctrl+Shift+N      `                | New window/instance                     |
| `Ctrl+Shift+W      `                | Close window/instance                   |
| `Ctrl+,            `                | User Settings                           |
| `Ctrl+K Ctrl+S     `                | Keyboard Shortcuts                      |

## Basic editing

| <div style="width:200px">Keys</div> | <div style="width:400px">Shortcut</div> |
| :---------------------------------- | :-------------------------------------- |
| `Ctrl+X            `                | Cut line (empty selection)              |
| `Ctrl+C            `                | Copy line (empty selection)             |
| `Alt+ ↑ / ↓        `                | Move line up/down                       |
| `Shift+Alt + ↓ / ↑ `                | Copy line up/down                       |
| `Ctrl+Shift+K      `                | Delete line                             |
| `Ctrl+Enter        `                | Insert line below                       |
| `Ctrl+Shift+Enter  `                | Insert line above                       |
| `Ctrl+Shift+\      `                | Jump to matching bracket                |
| `Ctrl+] / [        `                | Indent/outdent line                     |
| `Home / End        `                | Go to beginning/end of line             |
| `Ctrl+Home         `                | Go to beginning of file                 |
| `Ctrl+End          `                | Go to end of file                       |
| `Ctrl+↑ / ↓        `                | Scroll line up/down                     |
| `Alt+PgUp / PgDn   `                | Scroll page up/down                     |
| `Ctrl+Shift+[      `                | Fold (collapse) region                  |
| `Ctrl+Shift+]      `                | Unfold (uncollapse) region              |
| `Ctrl+K Ctrl+[     `                | Fold (collapse) all subregions          |
| `Ctrl+K Ctrl+]     `                | Unfold (uncollapse) all subregions      |
| `Ctrl+K Ctrl+0     `                | Fold (collapse) all regions             |
| `Ctrl+K Ctrl+J     `                | Unfold (uncollapse) all regions         |
| `Ctrl+K Ctrl+C     `                | Add line comment                        |
| `Ctrl+K Ctrl+U     `                | Remove line comment                     |
| `Ctrl+/            `                | Toggle line comment                     |
| `Shift+Alt+A       `                | Toggle block comment                    |
| `Alt+Z             `                | Toggle word wrap                        |

## Navigation

| <div style="width:200px">Keys</div> | <div style="width:400px">Shortcut</div> |
| :---------------------------------- | :-------------------------------------- |
| `Ctrl+T              `              | Show all Symbols                        |
| `Ctrl+G              `              | Go to Line...                           |
| `Ctrl+P              `              | Go to File...                           |
| `Ctrl+Shift+O        `              | Go to Symbol...                         |
| `Ctrl+Shift+M        `              | Show Problems panel                     |
| `F8                  `              | Go to next error or warning             |
| `Shift+F8            `              | Go to previous error or warning         |
| `Ctrl+Shift+Tab      `              | Navigate editor group history           |
| `Alt+ ← / →          `              | Go back / forward                       |
| `Ctrl+M              `              | Toggle Tab moves focus                  |

## Search and replace

| <div style="width:200px">Keys</div> | <div style="width:400px">Shortcut</div>    |
| :---------------------------------- | :----------------------------------------- |
| `Ctrl+F                  `          | Find                                       |
| `Ctrl+H                  `          | Replace                                    |
| `F3 / Shift+F3           `          | Find next/previous                         |
| `Alt+Enter               `          | Select all occurences of Find match        |
| `Ctrl+D                  `          | Add selection to next Find match           |
| `Ctrl+K Ctrl+D           `          | Move last selection to next Find match     |
| `Alt+C / R / W           `          | Toggle case-sensitive / regex / whole word |

## Multi-cursor and selection

| <div style="width:200px">Keys</div> | <div style="width:400px">Shortcut</div>     |
| :---------------------------------- | :------------------------------------------ |
| `Alt+Click                       `  | Insert cursor                               |
| `Ctrl+Alt+ ↑ / ↓                 `  | Insert cursor above / below                 |
| `Ctrl+U                          `  | Undo last cursor operation                  |
| `Shift+Alt+I                     `  | Insert cursor at end of each line selected  |
| `Ctrl+L                          `  | Select current line                         |
| `Ctrl+Shift+L                    `  | Select all occurrences of current selection |
| `Ctrl+F2                         `  | Select all occurrences of current word      |
| `Shift+Alt+→                     `  | Expand selection                            |
| `Shift+Alt+←                     `  | Shrink selection                            |
| `Shift+Alt + (drag mouse)        `  | Column (box) selection                      |
| `Ctrl+Shift+Alt + (arrow key)    `  | Column (box) selection                      |
| `Ctrl+Shift+Alt+PgUp/PgDn        `  | Column (box) selection page up/down         |

## Rich languages editing

| <div style="width:200px">Keys</div>    | <div style="width:400px">Shortcut</div> |
| :------------------------------------- | :-------------------------------------- |
| `Ctrl+Space, Ctrl+I                  ` | Trigger suggestion                      |
| `Ctrl+Shift+Space                    ` | Trigger parameter hints                 |
| `Shift+Alt+F                         ` | Format document                         |
| `Ctrl+K Ctrl+F                       ` | Format selection                        |
| `F12                                 ` | Go to Definition                        |
| `Alt+F12                             ` | Peek Definition                         |
| `Ctrl+K F12                          ` | Open Definition to the side             |
| `Ctrl+.                              ` | Quick Fix                               |
| `Shift+F12                           ` | Show References                         |
| `F2                                  ` | Rename Symbol                           |
| `Ctrl+K Ctrl+X                       ` | Trim trailing whitespace                |
| `Ctrl+K M                            ` | Change file language                    |

## Editor management

| <div style="width:200px">Keys</div> | <div style="width:400px">Shortcut</div> |
| :---------------------------------- | :-------------------------------------- |
| `Ctrl+F4, Ctrl+W                 `  | Close editor                            |
| `Ctrl+K F                        `  | Close folder                            |
| `Ctrl+\                          `  | Split editor                            |
| `Ctrl+ 1 / 2 / 3                 `  | Focus into 1st, 2nd or 3rd editor group |
| `Ctrl+K Ctrl+ ←/→                `  | Focus into previous/next editor group   |
| `Ctrl+Shift+PgUp / PgDn          `  | Move editor left/right                  |
| `Ctrl+K ← / →                    `  | Move active editor group                |

## File management

| <div style="width:200px">Keys</div>    | <div style="width:400px">Shortcut</div> |
| :------------------------------------- | :-------------------------------------- |
| `Ctrl+N                              ` | New File                                |
| `Ctrl+O                              ` | Open File...                            |
| `Ctrl+S                              ` | Save                                    |
| `Ctrl+Shift+S                        ` | Save As...                              |
| `Ctrl+K S                            ` | Save All                                |
| `Ctrl+F4                             ` | Close                                   |
| `Ctrl+K Ctrl+W                       ` | Close All                               |
| `Ctrl+Shift+T                        ` | Reopen closed editor                    |
| `Ctrl+K Enter                        ` | Keep preview mode editor open           |
| `Ctrl+Tab                            ` | Open next                               |
| `Ctrl+Shift+Tab                      ` | Open previous                           |
| `Ctrl+K P                            ` | Copy path of active file                |
| `Ctrl+K R                            ` | Reveal active file in Explorer          |
| `Ctrl+K O                            ` | Show active file in new window/instance |

## Display

| <div style="width:200px">Keys</div>     | <div style="width:400px">Shortcut</div>    |
| :-------------------------------------- | :----------------------------------------- |
| `F11                                  ` | Toggle full screen                         |
| `Shift+Alt+0                          ` | Toggle editor layout (horizontal/vertical) |
| `Ctrl+ = / -                          ` | Zoom in/out                                |
| `Ctrl+B                               ` | Toggle Sidebar visibility                  |
| `Ctrl+Shift+E                         ` | Show Explorer / Toggle focus               |
| `Ctrl+Shift+F                         ` | Show Search                                |
| `Ctrl+Shift+G                         ` | Show Source Control                        |
| `Ctrl+Shift+D                         ` | Show Debug                                 |
| `Ctrl+Shift+X                         ` | Show Extensions                            |
| `Ctrl+Shift+H                         ` | Replace in files                           |
| `Ctrl+Shift+J                         ` | Toggle Search details                      |
| `Ctrl+Shift+U                         ` | Show Output panel                          |
| `Ctrl+Shift+V                         ` | Open Markdown preview                      |
| `Ctrl+K V                             ` | Open Markdown preview to the side          |
| `Ctrl+K Z                             ` | Zen Mode (Esc Esc to exit)                 |

## Debug

| <div style="width:200px">Keys</div>    | <div style="width:400px">Shortcut</div> |
| :------------------------------------- | :-------------------------------------- |
| `F9                                  ` | Toggle breakpoint                       |
| `F5                                  ` | Start/Continue                          |
| `Shift+F5                            ` | Stop                                    |
| `F11 / Shift+F11                     ` | Step into/out                           |
| `F10                                 ` | Step over                               |
| `Ctrl+K Ctrl+I                       ` | Show hover                              |

## Integrated terminal

| <div style="width:200px">Keys</div>   | <div style="width:400px">Shortcut</div> |
| :------------------------------------ | :-------------------------------------- |
| `Ctrl+` `                             | Show integrated terminal                |
| `Ctrl+Shift+` `                       | Create new terminal                     |
| `Ctrl+C                             ` | Copy selection                          |
| `Ctrl+V                             ` | Paste into active terminal              |
| `Ctrl+↑ / ↓                         ` | Scroll up/down                          |
| `Shift+PgUp / PgDn                  ` | Scroll page up/down                     |
| `Ctrl+Home / End                    ` | Scroll to top/bottom                    |

Other operating systems’ keyboard shortcuts and additional unassigned shortcuts available at [Official VS Code docs](https://code.visualstudio.com/docs/getstarted/keybindings)
