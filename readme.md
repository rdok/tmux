### Habits

| Description                                               | Command                               |
| ----------------------------------------------------------|:--------------------------------------|
| Create a session named(target) 'basic'.                   | `tmux new -s basic`                   |
| Create a session in the background.                       | `tmux new -s basic -d`                |
| Execute command in tmux. E.g. `<Ctrl-b>t`                 | `<Ctrl-b>{command}`                   |
| Detach from session. E.g. while running  `top`.           | `<Ctrl-b>d`                           |
| Attach default session.                                   | `tmux attach`                         |
| Attach to a session by target.                            | `tmux attach -t {target}`             |
| Kill a session by target, e.g. when a program is hanging. | `tmux kill-session -t {target}`       |

