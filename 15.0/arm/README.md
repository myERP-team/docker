# Odoo docker image adaptation for ARM64

[docker::pulls]: https://img.shields.io/docker/pulls/mailserver/docker-mailserver.svg?style=for-the-badge&logo=docker&logoColor=white

This fork from the [official docker repo](https://github.com/odoo/docker) add an adaptation from the docker file to provide compatibility under arm64.


To create your own image (arm64v8) and push it on your repo:

```buildx build --platform linux/arm64/v8 -t your-repo/your-image:your-tag --push .```


The image is available on [docker hub](https://hub.docker.com/r/alex35469/odoo-arm64v8 )
