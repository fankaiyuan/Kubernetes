A simple ubuntu based docker image with netcat installed. For testing ports TCP/UDP connections

**Note:** k8s pod needs process running to avoid being closed. Command line is used to create an nc service.

``kubectl exec -it nc-pod -- /bin/bash``

``nc [destination] [ports]``

``nc -l [ports]``
```
-u UDP
-v verbose
-l listening 
-k keep inbound sockets
-p specify local port
```
