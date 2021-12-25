# iperf3 service in a Docker container

## Install Docker and Docker-compose

### Linux

Install Docker and select Docker CE is fine.
Install docker-compose.

## Run it

```shell
> git clone git@github.com:odayny/iperf3-docker-compose
> cd iperf3-docker-compose
> docker-compose up -d
```

## On client

```shell
iperf3 -c <Dcoker host IP address>
```
