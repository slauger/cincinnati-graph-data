# cincinnati-graph-data

Nightly build of image with embedded [cincinnati-graph-data](https://github.com/openshift/cincinnati-graph-data). Can be used as init container for the OpenShift Update Service operator.

The image is available on [quay.io](https://quay.io/repository/slauger/cincinnati-graph-data).

## Run Build

Define an alternative image name or tag.

```
export CONTAINER_NAME=quay.io/slauger/cincinnati-graph-data
export CONTAINER_TAG=latest
```

Build, test and push.

```
make build
make test
make push
```
