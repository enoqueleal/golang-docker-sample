# Golang in Docker Container Sample

```bash
# build
$ docker build -t hello-world-image .

# run
$ docker run -p 3000:3000 -it --rm --name hello-world hello-world-image

```