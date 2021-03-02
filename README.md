tmuxrc
======

My Tmux configuration.

## Usage & Installation :
You can clone this repos in your home directory, like:
```
$ git clone https://github.com/GuillaumeSeren/tmuxrc ~/.tmux
# Add a link to the tmuxrc
$ ln -s ~/.tmux/tmux.conf ~/.tmux.conf
```

## Load the config on a existing session :

```
C^b :source-file ~/.tmux.conf
# Then it will to clone the tpm plugin if needed

C^b I # Install all the plugins and reload the profile

TMUX environment reloaded.
Done, press ENTER to continue.
```
