# jarvis-rest-api-server

Simple Flask rest api server to make jarvis say something.

    python jarvis-rest-api-server.py

You can edit the config inside properties.txt: jarvis_home, host, port

Example api call : 

    curl -X POST -H "Content-Type: application/json" -d '{"message":"test pour jarvis"}' http://127.0.0.1:6543/jarvissay
