## Setting up tmux

Run the following commands to install tmux:

```sh
sudo apt update
sudo apt install tmux
```

Then run the following command to install tpm (Tmux Package Manager):

```sh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm --depth 1
```

Remove the config folder and clone this repository as a replacement.

```
rm -rf ~/.config/tmux
git clone https://github.com/NarendraPatwardhan/terminalconfig ~/.config/tmux/
```

To start a new named session, run

```sh
tmux new -s ${Session}
```

To rename the window more appropriately, type `<ctrl>+<space> , ${WINDOW}`

To learn more about tmux use: https://tmuxcheatsheet.com/
