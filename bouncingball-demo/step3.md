# Open new terminal 

# Change directory
Execute `cd crossbar-examples/getting-started`{{execute}} to change to the getting-started directory.

# T1
Execute ` docker run -v $PWD:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python /app/ball.py`{execute T2}} to start the ball

#T2
Execute ` docker run -v $PWD:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python /app/ball.py`{execute T3}} to start the ball
