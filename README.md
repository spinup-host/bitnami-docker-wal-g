
# What is WAL-G?

> WAL-G is an archival restoration tool for PostgreSQL. WAL-G uses LZ4, LZMA, or Brotli compression, multiple processors, and non-exclusive base backups for Postgres.

[Overview of WAL-G](https://wal-g.org/)

# TL;DR

```console
$ docker run --name wal-g bitnami/wal-g:latest
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading Linux distribution.
* All Bitnami images available in Docker Hub are signed with [Docker Content Trust (DCT)](https://docs.docker.com/engine/security/trust/content_trust/). You can use `DOCKER_CONTENT_TRUST=1` to verify the integrity of the images.
* Bitnami container images are released daily with the latest distribution packages available.


> This [CVE scan report](https://quay.io/repository/bitnami/wal-g?tab=tags) contains a security report with all open CVEs. To get the list of actionable security issues, find the "latest" tag, click the vulnerability report link under the corresponding "Security scan" field and then select the "Only show fixable" filter on the next page.

# Supported tags and respective `Dockerfile` links

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/tutorials/understand-rolling-tags-containers/).


* [`1`, `1-debian-10`, `1.1.0`, `1.1.0-debian-10-r9` (1/debian-10/Dockerfile)](https://github.com/bitnami/bitnami-docker-wal-g/blob/1.1.0-debian-10-r9/1/debian-10/Dockerfile)

Subscribe to project updates by watching the [bitnami/wal-g GitHub repo](https://github.com/bitnami/bitnami-docker-wal-g).

# Get this image

The recommended way to get the Bitnami wal-g Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/bitnami/wal-g).

```console
$ docker pull bitnami/wal-g:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/bitnami/wal-g/tags/) in the Docker Hub Registry.

```console
$ docker pull bitnami/wal-g:[TAG]
```

If you wish, you can also build the image yourself.

```console

```

# Configuration

## Running commands

To run commands inside this container you can use `docker run`, for example to execute `wal-g --version` you can follow the example below:

```console
$ docker run --rm --name wal-g bitnami/wal-g:latest -- wal-g --version
```

Check the [official WAL-G documentation](https://github.com/wal-g/wal-g#configuration) for a list of the available parameters.

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-wal-g/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-wal-g/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-wal-g/issues/new). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License

Copyright 2021 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
