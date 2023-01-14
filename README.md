## Here's my tmux configuration. 

**Warning:** This build uses `~/.config/tmux/` as a working directory, if you already have a `~/.tmux.conf` you will need first run `rm -rf ~/.tmux.conf`.

Now, one way to set things up is by running:
```
git clone --recursive https://github.com/udkfer/tmux.git ~/.config/tmux/
tmux
prefix + I
tmux source ~/.config/tmux/tmux.conf
```
and you should be good to go.
Thank you.
