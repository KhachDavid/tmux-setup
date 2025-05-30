# To setup follow these two articles in order

Step 1: Install tmux

```bash
sudo apt install tmux
```

Step 2: Create a tmux session

```bash
tmux new -s SESSION_NAME
```

Step 3: Clone the tmux plugin manager repository

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Step 4: For yank

After installing, you will have to restart a new tmux session for copying to take effect

```bash
# GNOME on Ubuntu 22+
sudo apt install wl-clipboard

# Everything else
sudo apt install xclip
```

Step 5: Add the custom tmux configs

```bash
touch ~/.tmux.conf
# Copy the conf file contents of this repository to this file
tmux source ~/tmux.conf
# While in a tmux session, press Ctrl+X and I (uppercase I)
# This will start downloading and you are all set
```

## Sources

### Tmux Plugin Manager

[Link 1](https://ostechnix.com/install-tmux-plugin-manager/)

### Tmux Save and Restore 

[Link 2](https://ostechnix.com/save-and-restore-tmux-environment/)

### Tmux Cheat Sheet For References

[Link 3](https://tmuxcheatsheet.com/)

