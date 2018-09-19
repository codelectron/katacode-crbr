# Start Autobahn Python Publisher in Dockers 
Execute ` docker run -v $PWD:/app -e CBURL="ws://crossbar:8080/ws" -e CBREALM="realm1" --link=crossbar --rm -it crossbario/autobahn-python:cpy3 python /app/1.hello-world/client_component_publish.py`{{execute HOST1}} to run Autobahn Python publisher client in dockers.
