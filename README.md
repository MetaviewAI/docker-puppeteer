A minimal [Docker](https://www.docker.com/) image with [Google Puppeteer](https://developers.google.com/web/tools/puppeteer/) installed. The image also includes [X virtual framebuffer (Xvfb)](https://en.wikipedia.org/wiki/Xvfb) so that Chrome can be run in headful mode.

## Build

The latest official build can be found on [Docker Hub](https://cloud.docker.com/repository/docker/metaview/puppeteer/). To build the image locally, clone this repository and run the following command:

```shell
$ docker build -t metaview/puppeteer .
```

# Publish

To publish the latest changes to DockerHub:

```shell
$ docker push metaview/puppeteer:latest
```
