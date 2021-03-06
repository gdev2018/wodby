# About this Repo

[![Build Status](https://travis-ci.com/wodby/base-solr.svg?branch=master)](https://travis-ci.com/wodby/base-solr)
[![Docker Pulls](https://img.shields.io/docker/pulls/wodby/base-solr.svg)](https://hub.docker.com/r/wodby/base-solr)
[![Docker Stars](https://img.shields.io/docker/stars/wodby/base-solr.svg)](https://hub.docker.com/r/wodby/base-solr)
[![Docker Layers](https://images.microbadger.com/badges/image/wodby/base-solr.svg)](https://microbadger.com/images/wodby/base-solr)

This is the fork of https://github.com/docker-solr/docker-solr. After https://github.com/docker-solr/docker-solr/issues/213 there's no more alpine-based Solr images because alpine-based `_/openjdk` was removed. This image builds only alpine-based variants for Solr based on [adoptopenjdk](https://adoptopenjdk.net)  alpine-based images.  

## Docker Images

* All images are based on Alpine Linux
* Base image: [adoptopenjdk/openjdk8](https://hub.docker.com/r/adoptopenjdk/openjdk8) or [adoptopenjdk/openjdk11](https://hub.docker.com/r/adoptopenjdk/openjdk11)
* [Travis CI builds](https://travis-ci.org/wodby/base-solr) 
* [Docker Hub](https://hub.docker.com/r/wodby/base-solr)

Supported tags and respective `Dockerfile` links

* `8.4.0`, `8.4`, `8`, `latest` [_(8.4/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/8.4/alpine/Dockerfile)
* `8.3.0`, `8.3` [_(8.3/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/8.3/alpine/Dockerfile)
* `8.2.0`, `8.2` [_(8.2/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/8.2/alpine/Dockerfile)
* `8.1.1`, `8.1` [_(8.1/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/8.1/alpine/Dockerfile)
* `8.0.0`, `8.0` [_(8.0/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/8.0/alpine/Dockerfile)
* `7.7.2`, `7.7`, `7` [_(7.7/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/7.7/alpine/Dockerfile)
* `7.6.0`, `7.6` [_(7.6/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/7.6/alpine/Dockerfile)
* `7.5.0`, `7.5` [_(7.5/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/7.5/alpine/Dockerfile)
* `6.6.6`, `6.6`, `6` [_(6.6/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/6.6/alpine/Dockerfile)
* `5.5.5`, `5.5`, `5` [_(5.5/alpine/Dockerfile)_](https://github.com/wodby/base-solr/tree/master/5.5/alpine/Dockerfile)

## Image with config sets

We have [wodby/solr](https://github.com/wodby/solr) image based on this image that contains built-in config sets (currently only Drupal).  

## Maintenance

Synced with the upstream and auto-updated via [wodby/images](https://github.com/wodby/images)
