# Rabbitmq Delayed Message Exchange Docker Image
Docker image based on official rabbitmq with additional delayed message exchange plugin and cross compiled for differente architecures (AMD64 and ARM).

You can pull the image directly from the docker hub [here](https://hub.docker.com/repository/docker/fschuindt/rabbitmq-delayed-message-exchange).

# How to build
 * Go in the root of this project
 * docker build -t <IMAGE_NAME>:<IMAGE_TAG> .

## Building multi arch

You can build it for different architectures by using ```buildx``` in your Docker desktop. This allows this image for example to run not only on amd64, but also on arm/v7 and arm64. This is a must, for example, if you want to run this image on raspberry pi which runs on an ARM processor.

You can follow the instructions [here](https://collabnix.com/building-arm-based-docker-images-on-docker-desktop-made-possible-using-buildx/).

# Releases

This repo only has one Dockerfile. To navigate to different versions, check the Releases page of this repo. 
