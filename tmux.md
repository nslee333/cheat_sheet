tmux commands

tmux -> start tmux

ctrl b + d -> exit tmux

ctrl b,c -> new window

ctrl + b [0...9] -> switch to N window.

ctrl + b [ -> scroll mode, pgUp pgDwn for scrolling 
  q to exit

ctrl + b % -> split current pane with a vertical line

ctrl + b ; -> go to last active terminal

## other notes:

If you ever modify .tmux.conf make sure you run this command:
  - `tmux source-file ~/.tmux.conf`
  - restarting your pc also works :)
