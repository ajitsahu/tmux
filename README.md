# tmux
# Unbind 'b' with backtik key '`'
unbind C-b
set -g prefix `
bind ` send-prefix
bind-key L last-window
set -g default-terminal "screen-256color"
#split window with vertical bar and hypen
bind | split-window -h
bind - split-window -v
set -g base-index 1
#set history limit 
set -g history-limit 30000
