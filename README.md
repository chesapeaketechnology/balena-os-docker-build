# balena-os-docker-build
Builds yocto environment in Docker for building Balena images or other Yocto layers.

To build a default raspberry pi image:
```
$ docker-compose up
```

You can also specify revisions and platforms to build by setting environment variables:

```
REPO=https://github.com/balena-os/balena-raspberrypi.git
MACHINE=raspberrypi
```

