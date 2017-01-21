#Docker-Test
A test application for containerizing a node application through Docker.

#### Building your image
```
$ docker build -t node-app .
```

#### Check images
```
$ docker images
```

#### Run the image
```
$ docker run -p 49160:8080 -d node-app
```

#### Print out some details
```
# Get container ID
$ docker ps

# Print app output
$ docker logs <container id>
```


#### Get inside the container
```
$ docker exec -it <container id> /bin/bash
```



