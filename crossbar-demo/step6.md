# Open new terminal 
Lets start a new terminal `ssh root@host01`{{execute T4}} 

# Change directory
The `cd crossbar-examples/getting-started`{{execute}} will change to the getting-started directory.

# Start Autobahn Python RPC Caller in Dockers 
Execute ` docker run -v $PWD:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python /app/3.rpc/client_component_rpc_caller.py`{{execute T3}} to run Autobahn Python RPC Caller  in dockers.
