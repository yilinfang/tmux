# tmux

Personal tmux configuration.

## Requirements

- tmux `>= 2.6`
- tmux `>= 3.0` is recommended for the best experience

## Installation

**Remember to backup your current configuration!!!**

**Option 1: install to `~/.config/tmux`**

```bash
git clone https://github.com/yilinfang/tmux.git ~/.config/tmux
tmux kill-server
```

**Option 2: install to `~/.tmux.conf`**

```bash
curl -o ~/.tmux.conf https://raw.githubusercontent.com/yilinfang/tmux/master/tmux.conf
tmux kill-server
```
