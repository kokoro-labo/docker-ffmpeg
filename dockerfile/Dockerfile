FROM jrottenberg/ffmpeg:4.1-ubuntu

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y \
    tzdata && \
    apt-get clean