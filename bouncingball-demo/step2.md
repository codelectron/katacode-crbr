# Split 
Execute `tmux`{{execute}} and change to the getting-started directory.

# Split 
Execute `tmux  split-window`{{execute}} and change to the getting-started directory.

# Start Bouncing ball demo in window 1

Execute ` tmux send-keys -t $SESSION:0.1  'docker run -v $PWD/crossbar_ball_demo:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python ball.py --node=0 ' C-m`{{execute}} to run Crossbar.io in dockers with configuration mounted from getting-started folder.


