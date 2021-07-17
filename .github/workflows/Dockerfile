FROM debian:bullseye

COPY . /usr/local/

RUN apt update && apt install -y --no-install-recommends gdb

CMD [ "protoc" ]
