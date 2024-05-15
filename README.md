
## Setup
From the cloned directlory, run `./setup.sh`. This will do the following:

1. Create the directories `plugins/tpm/` in the current root directory
2. Create a softlink, `~/.tmux.conf`, to the tmux.conf file in the current root directory
3. Run the Tmux Plugin Manager so that any referenced plugins within the tmux.conf file are pulled down
4. Running `./setup.sh` will always check if the above files and directories are already present and will exit if it finds them.

## Remove
From the cloned directory, run `./remove.sh`. This will do the following:

1. Delete the softlink, `~/.tmux.conf`
2. Delete the cloned directory and all its contents (which will also delete the file `remove.sh`)
