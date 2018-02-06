# docker-wget
A minimal Docker image with wget based on alpine. 

This is the Git repo for the Docker image built automatically at Docker Hub - 
[jgoclawski/wget](https://hub.docker.com/r/jgoclawski/wget/).
Nothing fancy, but based on alpine 3.7 with working TLS certificate validation, which
is a problem in other wget images.

## Usage

```bash
docker run --rm -it jgoclawski/wget wget https://www.gnu.org/software/wget/

```

## Building

```bash
docker build wget -t jgoclawski/wget

```
