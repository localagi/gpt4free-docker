# gpt4free-docker

Sophisticated docker builds for parent project [xtekky/gpt4free](https://github.com/xtekky/gpt4free). 

![example workflow](https://github.com/localagi/gpt4free-docker/actions/workflows/publish-docker.yml/badge.svg?branch=main)

###### (*Parent* projects docker state for tracking: ![example workflow](https://github.com/xtekky/gpt4free/actions/workflows/ci.yml/badge.svg?branch=main) )

Easy setup. Compatible. Tweakable. Scaleable.

#### Supported platforms
`amd64`, `arm64`

#### Supported versions
`main`

See [Releases](../../releases)

## Prerequisites

* `docker` and `docker compose` are available on your system

## Run

* get `docker-compose.yml` (clone repo, copy or else) 
* Run `docker compose up`
* open/refresh `http://localhost:8501` 

### Get the latest builds / update
`docker compose pull`

### Cleanup
`docker compose rm`

## Contributing

When there is a new version and there is need of builds or you require the latest main build, feel free to open an issue

## Problems?

Open an issue on the [Issue Tracker](../../issues)

## Limitations
We cannot support issues regarding the base software. Please refer to the main project page mentioned in the second line of this card.
