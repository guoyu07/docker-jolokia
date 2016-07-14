docker-jolokia
==============

Minimal Image with Apache Tomcat8, openjdk8-jre-base and jolokia.

# Status
[![Build Status](https://travis-ci.org/bodsch/docker-jolokia.svg?branch=master)](https://travis-ci.org/bodsch/docker-jolokia)

# Build

Your can use the included Makefile.

To build the Container:
```make build```

Starts the Container:
```make run```

Starts the Container with Login Shell:
```make shell```

Entering the Container:
```make exec```

Stop (but **not kill**):
```make stop```

# Docker Hub

You can find the Container also at  [DockerHub](https://hub.docker.com/r/bodsch/docker-jolokia/)


# Versions

 - tomcat 8.5.4
 - jolokia 1.3.3
 - openjdk from alpine

```

# Test

    curl http://localhost:8080/jolokia/ | python -mjson.tool


# Ports

* 8080

