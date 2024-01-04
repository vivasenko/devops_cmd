# start just new session:
    tmux 
# create concrete session:
    tmux new -s <name>
    tmux ls
# attach recent session:
    tmux a

### Hot-keys:
# split screen vertical:
    c-b(Ctrl + B) + Shift+5 (for 50%)

# split screen horisontal:
    c-b + Shift+"

# move window (use alt key for bigger steps):
    c-b + ctrl+<Arrow_key>
# navigation:
    c-b + <Arrow_key>

# delete current:
    Ctrl+D

# display index:
    c-b + Q
# jump to concrete index window:
    c-b + Q - <index_value>

# align all windows: 1-vertical, 2-horisontal, 3,4, 5-4ssquares:
    c-b + Alt+1

# create new window:
    c-b + C
# return:
    c-b + N

# rename window:
    c-b + ,

# show all sessions + navigate between:
    c-b + W
# delete from session:
    c-b + X
# kill concrete window:
    c-b + x
# kill all window:
    c-b + x &

# to copy:
# create session file: .tmux.conf with next cmd:
    set -g mouse on
    setw -g mode-keys vi

# kill all sessions:
    tmux kill-server

# copy:
    c-b + [
# paste:
    c-b + ]


