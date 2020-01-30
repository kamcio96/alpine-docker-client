Alpine-docker-client (author: https://github.com/Cethy/alpine-docker-client)
===

## Usage
You need to pass docker's socket to container

    # display stats
    docker run --rm -it -v /var/run/docker.sock:/var/run/docker.sock kamcio96/alpine-docker-client docker stats
