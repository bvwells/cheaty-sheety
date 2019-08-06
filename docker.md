# Random docker commands I forgety

## Image and container commands

List running containers:
```
docker ps
```

List images:
```
docker images
```

List container logs:
```
docker logs container-name
```

List container port:
```
docker port container-name
```

Run docker image:
```
docker run -it image_name
```

Run docker image forwarding port:
```
docker run -it -p host_port:container_port image_name
```

Run docker image mapping volume:
```
docker run -it -v host_path:container_path image_name
```

Delete a running container:
```
docker rm -f container_name
```

Delete an image:
```
docker rmi image_name
```

Tag an image:
```
docker tag image_name:tag image_name:new_tag
```

Build an image:
```
docker build -t image_name:tag .
```



