# Open new terminal 
Lets start a new terminal `ssh root@host01`{{execute T3}} 

# Change directory
Execute `cd crossbar-examples/getting-started`{{execute}} will change to the getting-started directory.

# Start Autobahn Python Subscriber in Dockers 
Execute ` docker run -v $PWD:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python /app/1.hello-world/client_component_subscribe.py`{{execute T3}} to run Autobahn Python subscriber client in dockers.
