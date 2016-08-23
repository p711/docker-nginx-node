# Image Contents

[![](https://images.microbadger.com/badges/image/p711/docker-nginx-node.svg)](https://microbadger.com/images/p711/docker-nginx-node

This image is based on the [official nginx image](https://hub.docker.com/_/nginx/) and includes the features of that image.
The purpose of this image is to function as a build environment for static frontend applications, in this particular case for use in Gitlab CI.

At the time of writing, this Dockerfile results in an image that also contains:

* Docker client
* NodeJS 4.x (installed via [NodeSource](https://github.com/nodesource/distributions#debinstall)'s APT repository)
* npm 3.8.9

## Image Versions

The `latest` tag on Docker Hub should always be reasonably in sync with the tip of `master` within this repository via automated builds. 


