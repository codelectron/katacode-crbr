# Start the Tmux 
Execute `tmux`{{execute}} and change to the getting-started directory.

# Split the window 
Execute `tmux  split-window`{{execute}} and change to the getting-started directory.

# Start Bouncing ball demo in window 1

Execute ` tmux send-keys -t $SESSION:0.0  'docker run -v $PWD/crossbar_ball_demo:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python ball.py --node=1 ' C-m`{{execute}} to start the bouncing ball demo in window 1 with configuration mounted from crossbar_ball_demo folder.


