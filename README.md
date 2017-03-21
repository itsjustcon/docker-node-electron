# docker-node-electron
Node.js + Electron (+ xvfb + google-chrome-stable) so you can quickly dockerize virtual-browser-based apps! *(depends on [itsjustcon/docker-node-xvfb](https://github.com/itsjustcon/docker-node-xvfb))*

Head over to the [Docker Hub Repo](https://hub.docker.com/r/itsjustcon/node-electron) for more info.

### Build:
```
docker build --tag=itsjustcon/node-electron .
```

### Deploy:
*Be careful with this!* Docker Hub is configured for Automated Builds - meaning
this container image will be automatically re-built & updated on git push.
```
docker push itsjustcon/node-electron
```
