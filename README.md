Usage:

```
docker run -p 0.0.0.0:2800:80 --rm -it metacoma/ws2tcp
```

js 
```
var s = new WebSocket("ws://localhost:2800/ws2tcp?backend=<ip:port>)
```

