# TMUX

### New session

```sh
tmux
```

### New session with name

```sh
tmux new -s session_name
```

### Show all sessions

```sh
tmux ls
```

or
<kbd>Ctrl</kbd> + <kbd>B</kbd> then <kbd>s</kbd>

### Detach from current session

<kbd>Ctrl</kbd> + <kbd>B</kbd> then <kbd>d</kbd>


### Attach to session by name

```sh
tmux a -t session_name
```

### Kill session by name

```sh
tmux kill-ses -t session_name
```

### Split window horizontally

<kbd>Ctrl</kbd> + <kbd>B</kbd> then <kbd>%</kbd>

### Split windo vertically

<kbd>Ctrl</kbd> + <kbd>B</kbd> then <kbd>"</kbd>