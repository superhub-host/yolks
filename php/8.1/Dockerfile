FROM        --platform=$TARGETOS/$TARGETARCH php:8.1-bullseye
LABEL       maintainer="ruscalworld <me@ruscal.world>"

USER        container
ENV         USER=container HOME=/home/container
ENV         DEBIAN_FRONTEND noninteractive

WORKDIR     /home/container

COPY        ./../entrypoint.sh /entrypoint.sh
CMD         [ "/bin/bash", "/entrypoint.sh" ]
