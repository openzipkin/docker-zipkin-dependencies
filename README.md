[![Build Status](https://travis-ci.org/openzipkin/docker-zipkin-java.svg)](https://travis-ci.org/openzipkin/docker-zipkin-java)
[![zipkin-java](https://quay.io/repository/openzipkin/zipkin-java/status "zipkin-java")](https://quay.io/repository/openzipkin/zipkin-java)

# docker-zipkin-java

This repository contains the Docker build definition and release process for
[openzipkin/zipkin-java](https://github.com/openzipkin/zipkin-java), a native
java port of zipkin, which was historically written in scala+finagle.

Automatically built images are available on Quay.io
under the [OpenZipkin](https://quay.io/organization/openzipkin) organization, and are mirrored to
[Docker Hub](https://hub.docker.com/u/openzipkin/)

## Running

Use [docker-compose](https://docs.docker.com/compose/) by doing
`docker-compose up`.

See the ui at (docker ip):8080

In the ui - click zipkin-query, then click "Find Traces".