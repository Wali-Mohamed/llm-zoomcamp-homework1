docker commands
#this is docker hub for keeping all images
docker run hello-world

#running bash command in the ubuntu image
docker run -it ubuntu bash

# run python
docker run -it python:3.9
# makes it start with bash before going to python
docker run -it --entrypoint=bash python:3.9



