# golang-ubuntu-builder

A Docker image for building golang projects.  This image is derived from the [official](https://hub.docker.com/_/golang/) golang image.

It includes additional useful go packages:

* [dep](github.com/golang/dep/cmd/dep)
* [golangci-lint](https://github.com/golangci/golangci-lint)
* [goverreport](https://github.com/mcubik/goverreport)
* [go-critic](https://go-critic.github.io)
* [ghost](https://github.com/elliotchance/ghost)

## Build

The image is available on [docker hub](https://hub.docker.com/r/damianoneill/golang-ubuntu-builder/), you can pull it as follows:

```sh
docker pull damianoneill/golang-ubuntu-builder
```

Alternatively, after checking out this repository, you can build it locally with the following command:

```sh
docker build -t="damianoneill/golang-ubuntu-builder" .
```
