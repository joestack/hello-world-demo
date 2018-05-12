# hello-world-demo

Two directories (blue and green) containing node.js and Dockerfile to create a containerized app.
Exposes web server on port 8080 as per ./server.js

Serving whether a blue or a green web server content ;-)

Creating both containers using:
```
for i in blue green ; do docker build -t hello-$i:latest ./$i ; done 
```

Exposes web server on port 8080 as per ./server.js

See **Dockerfile** for more details
