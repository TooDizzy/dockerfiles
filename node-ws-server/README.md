# Use

```bash
docker pull boldt/node-ws-server:0.0.1
docker run --rm --name node-ws-server -p 12345:8080 -d boldt/node-ws-server:0.0.1
docker logs -f node-ws-server
```


# Build and push

```bash
docker build -t boldt/docker-express-example:0.0.1 .
docker push boldt/docker-express-example:0.0.1
```

# Sources

* https://github.com/websockets/ws
* https://nodejs.org/en/docs/guides/nodejs-docker-webapp/