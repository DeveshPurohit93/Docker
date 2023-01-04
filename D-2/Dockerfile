
FROM ubuntu:16.04

LABEL Creator: "Devesh"

RUN apt-get update && apt-get install -y curl \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

RUN mkdir /home/Codes

ENV USER Devesh 
ENV SHELL /bin/bash
ENV LOGNAME Devesh

CMD ["bash"]


