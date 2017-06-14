# docker-nodejs-slim - a slim Docker container for Node.js

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-nodejs-slim/

# ABOUT

docker-nodejs-slim is a container for Node.js, made smaller with a few techniques:

* Switch base image from [ubuntu](https://registry.hub.docker.com/_/ubuntu/) to [alpine](https://registry.hub.docker.com/u/alpine/).

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-nodejs-slim node --version
v0.10.33
docker run --rm mcandre/docker-nodejs-slim npm --version
1.4.28
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
