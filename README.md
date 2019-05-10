# Docker image with Java, Maven and Python



## Description

- Docker with Ubuntu 16.04, Java 8, Maven 3.5.2 and Python3. The versions can be customized from the Dockerfile.

## Setup Dockerfile

1. Build the image:

   `docker build -t #{_name_image_} .`

2. Run an instance of the image, mounting the directory:

   `docker run -v /Users/#{your_user}/projects:/home/projects  #{_name_image_} `