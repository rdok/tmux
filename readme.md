## Habits

### Sessions

| Description                                               | Command                               |
| ----------------------------------------------------------|:--------------------------------------|
| Create a session named(target) 'basic'.                   | `tmux new -s basic`                   |
| Create a session in the background.                       | `tmux new -s basic -d`                |
| Execute command in tmux. E.g. show time `<Ctrl-b>t`       | `<Ctrl-b>{command}`                   |
| Detach from session. E.g. while running  `top`.           | `<Ctrl-b>d`                           |
| Attach default session.                                   | `tmux attach`                         |
| Attach to a session by target.                            | `tmux attach -t {target}`             |
| Kill a session by target, e.g. when a program is hanging. | `tmux kill-session -t {target}`       |


### Windows

| Description                                               | Command                               |
| ----------------------------------------------------------|:--------------------------------------|
| Create a window in a current session.                     | `<Ctr-b>c`                            |
| Rename a window.                                          | `<Ctr-b>,`                            |
| Move to next window.                                      | `<Ctr-b>n`                            |
| Move to previous window.                                  | `<Ctr-b>p`                            |
| Jump to numbered window.                                  | `<Ctr-b>{number}`                     |
| GUI windows.                                              | `<Ctr-b>w`                     |

### Panes

| Description                                               | Command                               |
| ----------------------------------------------------------|:--------------------------------------|
| Create a vertical pane.                                   | `<Ctrl-b>%`                           |
| Create a horizontal pane.                                 | `<Ctrl-b>"`                           |
| Cycle through the panes.                                  | `<Ctrl-b>o`                           |
| Cycle through pane layouts.                               | `<Ctrl-b><space>`                     |
| Force kill a pane.                                        | `<Ctrl-b>x`                           |
| Swap panes                                                | `<Ctrl-b>}`                           |
