# Fluentd Elasticsearch

- Installs [Fluentd](https://www.fluentd.org/) log forwarder.

## TL;DR

```console
helm repo add helm-charts https://prasanna12510.github.io/helm-charts
helm install prasanna12510/fluentd-elasticsearch
```


## Prerequisites

- Kubernetes 1.8+ with Beta APIs enabled

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm install --name my-release prasanna12510/fluentd-elasticsearch
```

The command deploys fluentd-elasticsearch on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
