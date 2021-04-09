# build image
docker build --pull --rm -f "ubuntu-snake/DockerFile" -t ubuntu-snake "ubuntu-snake" 

# run interactive image 
docker run --rm -it  ubuntu-snake:latest
