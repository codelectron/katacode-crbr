# Open new terminal 
Lets start a new terminal `ssh root@host01`{{execute T2}} 

# Change directory
The `cd crossbar-examples/getting-started`{{execute}} will change to the getting-started directory.

# Start Autobahn Python Publisher in Dockers 
Execute ` docker run -v $PWD:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python /app/1.hello-world/client_component_publish.py`{{execute T2}} to run Autobahn Python publisher client in dockers.
