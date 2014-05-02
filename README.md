# h5ai

[h5ai](http://larsjung.de/h5ai/) is a modern web server index.
This [docker](https://www.docker.io/) image makes it trivially easy to
spin up a webserver and start sharing your files through the web.

## Build

```bash
$ sudo docker build -t h5ai .
```

## Run

```bash
$ sudo docker run -it --rm -p 80:80 -v `pwd`:/var/www h5ai
```

