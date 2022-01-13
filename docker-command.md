build an image based on the dockerfile in the current directory. Tag it as '<dockerhub username/<service/image name>'
`docker build -t <dockerhub username>/<image name> .`

`docker run <image id or image tag>`

cerate and start container, but also override the default command
`docker run -it <image id or image tag> <cmd>`

`docker ps`

execute the given command in a running container
`docker exec -it <container id> <cmd>`

`docker logs <container id>`