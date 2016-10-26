# osixia/www-redirect

[![Docker Pulls](https://img.shields.io/docker/pulls/osixia/www-redirect.svg)][hub]
[![Docker Stars](https://img.shields.io/docker/stars/osixia/www-redirect.svg)][hub]
[![](https://images.microbadger.com/badges/image/osixia/www-redirect.svg)](http://microbadger.com/images/osixia/www-redirect "Get your own image badge on microbadger.com")

[hub]: https://hub.docker.com/r/osixia/www-redirect/

Latest release: 0.1.0 - [Changelog](CHANGELOG.md) | [Docker Hub](https://hub.docker.com/r/osixia/www-redirect/) 

**A docker image to redirect www.example.org to example.org or vice versa.**

This image is intended to be used behind a reverse proxy.

  - If the requested host is **www.example.org/whatever** the visitor will be redirected to **example.org/whatever**

  - If the requested host is **example.org/whatever** the visitor will be redirected to **www.example.org/whatever**


### Under the hood: osixia/web-baseimage

This image is based on osixia/web-baseimage.
More info: https://github.com/osixia/docker-web-baseimage

## Changelog

Please refer to: [CHANGELOG.md](CHANGELOG.md)
