# Kubernetes Guid

## build the docker image
Run command `docker build -t '066851930357/kubernetes-guide:1.0.0' .`

## run a docker container and enter into it
Run a command `docker run -it --rm -p 8080:80 '066851930357/kubernetes-guide:1.0.0'`

## exit from the container
Press keys `[Ctrl] + [C]`

## push changes to the Docker Hub
Run command `docker push '066851930357/kubernetes-guide:1.0.0'`

## pull the docker container from the Docker Hub
Run command `docker pull '066851930357/kubernetes-guide:1.0.0'`

## pull and run (without enter into the container)
Run command `docker run '066851930357/kubernetes-guide:1.0.0'`