# Start Bouncing ball demo in window 2

Execute ` docker run -v $PWD/crossbar_ball_demo:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python ball.py --node=0 --join=1:D:0`{{execute}} to start the bouncing ball demo in window 2 with configuration mounted from crossbar_ball_demo folder.
