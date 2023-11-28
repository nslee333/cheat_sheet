  1 set-option -g prefix C-b
  2 bind-key n last-window
  3 bind-key m send-prefix
  4
  5 set -g mouse on
  6 set -g status-position bottom
  7 set -g status-bg colour234
  8 set -g status-fg colour137
  9 set -g status-style dim
 10 set -g status-left ''
 11 set -g status-right '#[fg=colour233,bg=colour241,bold] %d/%m #[fg=colour233,bg=colour245,bold] %H:%M:%S '
 12 set -g status-right-length 50
 13 set -g status-left-length 20
 14
 15 setw -g window-status-current-style fg=colour81
 16 setw -g window-status-current-style bg=colour238
 17 setw -g window-status-current-style bold
 18 setw -g window-status-current-format ' #I#[fg=colour250]:#[fg=colour255]#W#[fg=colour50]#F '
 19
 20 setw -g window-status-style fg=colour138
 21 setw -g window-status-style bg=colour235
 22 setw -g window-status-style none
 23 setw -g window-status-format ' #I#[fg=colour237]:#[fg=colour250]#W#[fg=colour244]#F '
 24
 25 setw -g window-status-bell-style bold
 26 setw -g window-status-bell-style fg=colour255
 27 setw -g window-status-bell-style bg=colour1
~                                               